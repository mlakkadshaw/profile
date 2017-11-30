<template>
  <div class="feedback">
    <div v-bind:class="{ 'inverse': (index % 2 === 1) }" v-for="(feedback, index) in feedbacks" v-bind:key="index" class="feedback-item row auto align-center">
      <div class="col">
        <p>
          {{ feedback.message }}
        </p>
        <p class="author">
          {{ feedback.author }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Feedback',
  data () {
    return {
      feedbacks: [{
        message: `He is extremely fast, reliable and very good at all of the 
core technologies that are used on the project. I would wholeheartedly 
recommend Mohammed Lakkadshaw for any software development project 
involving cloud, web, HTML5, JavaScript or web/REST services technologies.  
He has been a delight to work with.`,
      author: 'Shoeb Javed, CTO Worksoft'
      }, {
        message: `Mohammed is awesome. I would hire them at the drop off an hat. `,
        author: 'Adam Benzion Co-Founder Hackster.io'
      }, {
        message: 'We had a good experience working with Mohammed. He is a versatile coder and was able to join our working project with little guidance. Good focus on details, and very good grasp on technologies.',
        author: 'Meitre (https://meitre.com/)'
      }]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.feedback-item {
  padding: 20px;
  background-color: #342C3C;
}

.author {
  	color: #d9b8b8;
}

.inverse {
	background-color: rgba(52, 44, 60, 0.87);

}
</style>
