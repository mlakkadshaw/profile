<template>
  <div class="projects">
    <div v-for="(project, index) in projects" v-bind:key="index" class="row gutters project">
      <div class="col col-3 push-middle">
        <img class='project-image' v-bind:src='project.image' />
      </div>
      
      <div class="col col-9">
        <p><strong>{{ project.title }}</strong></p>
      <p>Summary:</p>
      <p>
        {{ project.summary }}
      </p>
      <p>Technology:</p>
        <p>
          <span v-for="(tag, index) in project.tags" v-bind:key="index" class="label focus"  style="margin: 2px;">
            {{ tag }}
          </span>
        </p>
        <p>
          <a target="_blank" v-bind:href="project.button.url">{{ project.button.text }}</a>
        </p>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Projects',
  data () {
    return {
      projects: [{
        title: 'Dead Simple Screen Sharing',
        summary: `Built a screen-sharing application that allows users to share their screen and do audio conferencing. `,
        tags: ['node.js', 'mongodb', 'vue/vuex', 'google-cloud'],
        image: '/static/img/deadsimple.jpg',
        button: {
          text: 'Visit Website',
          url: 'https://www.deadsimplescreensharing.com'
        },
      },
      {
        title: 'TutorMe',
        summary: `Online teaching app that helps tutors and students meet over the internet. I have developed the real time collaboration part of the program which allows the collaborative whiteboard, screen sharing, audio video calling, chat, collaborative text and code editing.`,
        tags: ['node.js', 'django', 'webrtc', 'socket.io', 'aws'],
        image: '/static/img/tutorme.jpg',
        button: {
          text: 'Visit Website',
          url: 'https://www.tutorme.com'
        }
      }, {
        title: 'GetNugg',
        summary: `GetNugg is like Amazon for Marijuana. Various dispensaries list their products and patients with a medical card can buy different types of Cannabis from listed local dispensaries. using their mobile phones or computer and they get the Cannabis delivered to their home. I developed the mobile app and backend`,
        tags: ['node.js', 'mongodb', 'ionic', 'angular.js', 'aws'],
        image: '/static/img/nuggninja.png',
        button: {
          text: 'Visit Website',
          url: 'https://www.getnugg.com'
        },
      }, {
        title: 'RoomPro Global',
        summary: `I have built the Global Management System to control Room pro devices and systems across 20000 schools in North America. The interface is a website through which Room pro division heads and employees, schools and teachers can control room pro devices remotely, each with a specific access control over the system.`,
        tags: ['node.js', 'postgresql', 'react', 'aws'],
        image: '/static/img/roompro.jpg',
        button: {
          text: 'Visit Website',
          url: 'https://www.roomprotech.com'
        },
      },{
        title: 'Ghost Communications Platform',
        summary: `Developed a distributed crypto-curreny network
        in Node.JS that provides services like ephemiral
        messaging, file storage, video calling, chat,
        file storage in a secure and distributed manner
        without requiring a central server.`,
        tags: ['node.js', 'angular.js', 'webrtc', 'socket.io', 'go', 'redis'],
        image: '/static/img/chat_ghost.jpg',
        button: {
          text: 'Read the case study',
          url: 'http://www.mohammedlakkadshaw.com/chatGhostStudy.html'
        }
      }]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.project-image {
  padding: 10px;
}

.project {
  padding-top: 30px;
}
</style>
