<template>
<div class="faq">
  <hr>
  <h3>Why should we hire you?</h3>
  <p>
    Because I am an excellent problem solver. I can build and solve almost any
    problem. I am a fast learner and if I don't have necessary skills to solve the problem then I will
    learn those skills. I am a versatile developer and can work on almost any problem realted to software development.
  </p>
  <hr>  
  <h3>Will you give a coding test?</h3>
  <p>
   Do I look like a clown? and coding tests are stupid. But I can do a test project if you want
  </p>
  <hr>  
  <h3>Will you do a test project?</h3>
  <p>
    Yes
  </p>

  <!-- 
  <h3>Tell us about your approach to debugging with a relevant example?</h3>
    <p>
      <p>
        My approach to debugging is Top-down, I first focus on the problem and start to trace it backward determining where it goes wrong and then I fix the problem.
      </p>
  <p>
A recent bug I encountered was I had developed an application for a client, and that application receives the stripe subscription updates via a webhook.
This app was running fine in production for quite some time (more than 1 year).
  </p>
  <p>
Then suddenly a problem started to appear that successful payments were not getting updated in the database, as well as receipt emails were also not getting sent and the customer said that they didn't touch that part of the code.
  </p>
  <p>
So this was a bit strange, I started looking for problems I first checked whether the server is receiving the webhook or not and in the logs I could see that server was receiving the webhook, but even after receiving the webhook the data was not getting updated and when I tested that portion of the code locally using a test stripe account everything worked fine.
  </p>
  <p>
This indicated that there must be some other service that must be interfering to cause this problem, so I looked for other services in the production environment, so it turned out that they had recently hired another developer to integrate an online form like Wufoo and he created a worker process that runs every 500 ms or so, and that updates database, this update increments the _v field in MongoDB. 
  </p>
I figured that when the stripe webhook arrives, the server fetches the campaign info from the database, this fetched info is stored in a variable and before the server could save campaign info back into the database the parallel service updates the campaign this results in version mismatch and the campaign cannot be saved in the database.
    </p>
    <p>
I synced the working of the two services and this bug was resolved.
The tools I use for debugging Node.JS is the debugger in VSCode and chrome dev tools.
    </p>
    <p>

For Angular/Vue/React their chrome extensions are excellent and really helpful during debugging as you can view the state, in Vue.js you can also go back in time to a previous application state which is really cool.
    </p>
    <p>
In server-side production applications, I integrate Sentry to catch and fix any exceptions and generating the Node.JS flame graph from pref is also useful to debug bottlenecks in code in production.
    </p>
      </p>
    </p>
  <hr>  
  <h3>Tell us about your approach to testing?</h3>
  <p>
    <p>
      For almost all the large projects I write tests. If there is the time I write end-to-end tests as well using the Nightwatch and I almost always write unit tests and I use Karma, Mocha and Jasmine.
    </p>
    <p>
Writing tests give you the confidence that any changes you have made do not cause any unintended changes in the application and assures you that everything is working and the new changes are not breaking anything else, and I feel this confidence is well worth the time spent on writing tests.
    </p>
    <p>
Also, another benefit of writing tests is that it allows you to reason about the code that you have written from another perspective and the process of writing test itself makes the code more robust.
    </p>
    <p>
I am currently writing tests for a renewal script which I had written for a project, this script runs each night and renews the campaigns for the customer and it updates the information in the database as well as sends the emails, so it is essential that the information in the database is updated as well as the emails are also sent out.
    </p>
    <p>
So for that, I am loading mock data in the test MongoDB database before the script run, then emails are sent out using SendGrid and I am using a mail-listener Node.js module to listen for emails and check whether are arriving or not.
    </p>
    </p>
  </p>
  <hr>  
  <h3>How do you evaluate best pratices?</h3>
  <p>
    <p>
    There are lots of best practices out there and there are many practices which contradict each other, so before blindly accepting any approach I ask my self 3 questions to decided whether to follow the best practice or not:
    </p>
    <ol>
      <li>
        is it improving the code clarity? If the suggested practice is making the code more readable and if it is a project structure then is it making the structure more clear then I follow it
      </li>
      <li>
        Is it improving productivity? If suggested practice is improving my productivity for e.g a certain build tool or a recommended shortcut then I use it
      </li>
      <li>
      Will it help avoiding common bugs? If the suggest practice helps in avoiding common bugs then I will use it, for example, using class scoped CSS styles
      </li>
    </ol>
  <p>
If the suggested practice satisfies these three question then it's worth it, otherwise, I ignore it.
  </p>
  <p>
In React I found the practice of using Higher Order Components and the concept of smart and dumb components incredibly useful, and these concepts also translate into other modern Javascript frameworks like Vue.js
  </p>

  <p>
    Other Best Partices on the backed I follow include:
  </p>
  <ol>
    <li>
      Using Helmet middleware in express
    </li>
    <li>
      Using a Rate-limiter middleware in express
    </li>
    <li>
      Hashing password with different salt and store them in the database
    </li>
    <li>
      I also using ESLint with Javascript Style Guide to keep all my code consistent and in good shape.
    </li>
  </ol>
 -->
  </p>
</div>
</template>

<script>
export default {
  name: 'Faq',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.project-image {
  padding: 10px;
}
</style>
