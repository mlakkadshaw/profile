<template>
  <div id="app">
   <div class="row gutters align-center">
     <div class="col col-8">
       <div class="header">
        <h1>Mohammed Lakkadshaw</h1>
        <h2>Full-Stack Javascript Developer</h2>
       </div>
      <div class="summary">
        <p>
        Hey,
        </p>
        <p>
          I am Mohammed, I am looking for a remote full-time job. I am a primarily a web developer and I have +6 years of developing large scalable and robust web applications. But I know it is difficult to believe anything you read on the internet so I have a solid list of project, testimonials and even code samples to back my claim.
      </p>
      <p>
        <strong>What I am not?</strong>
        <p>
          I not a Rockstar Developer a.k.a brogrammer a.k.a ninja a.k.a Douchebag.
        </p>
        <strong>What I am?</strong>
        <p>
          I sensible developer who can get things done and I work well individually as well as with teams.
        </p>
      </p>
      </div>
     </div>
     <div class="col col-4" style="text-align: right; padding-right: 20px; padding-top: 20px;">
       <img class='hide-sm' style="max-width: 200px;" src='./assets/profile.jpg' />
       <p>Want to talk?</p>
        <a href="mailto:mohammed.lakkadshaw@gmail.com">mohammed.lakkadshaw@gmail.com</a>
        <a href="https://www.mohammedlakkadshaw.com">Website</a>
        <a href="https://www.mohammedlakkadshaw.com/blog">Blog</a>   
        <a href="https://github.com/mlakkadshaw">Github</a>     


        <ul class="nav">
          <strong>Contents</strong>
          <li>
            <a href="#skills">Skills</a>
          </li>
          <li>
            <a href="#testimonails">Interesting things said about me</a>
          </li>
          <li>
            <a href="#projects">Intresting Projects</a>
          </li>
          <li>
            <a href="#code">Code Samples</a>
          </li>
          <li>
            <a href="#opensoruce">Open Source</a>
          </li>
          <li>
            <a href="#education">Education</a>
          </li>
          <li>
            <a href="#blogs">Blog Posts</a>
          </li>
          <li>
            <a href="#faqs">FAQs</a>
          </li>
        </ul>
     </div>
   </div>

   <div class="row">
     <div id='skills' class="skills-header">
       <h2>Skills</h2>
       <!-- <p>You can click on skills to filter the projects</p> -->
       <p>This table shows an overview of skills that I have.</p>
     </div>
   </div>
   <div class="row">
     <table class="table">
       <thead>
         <tr>
           <th>Front-End</th>
           <th>Backend</th>
           <th>Database</th>
           <th>Cloud</th>
         </tr>
       </thead>
       <tbody>
         <tr>
          <td>React/Redux</td>
          <td>Node.JS</td>     
          <td>PostgreSQL</td> 
          <td>AWS</td>
         </tr>
         <tr>
          <td>Vue and Vuex</td>
          <td>Django/Flask</td>
          <td>MongoDB</td>
          <td>Google Cloud</td>
         </tr>
         <tr>
           <td>React Native</td>
           <td>Go</td>
           <td>Redis</td>
           <td>AWS Lambda</td>
         </tr>
         <tr>
           <td>Swift</td>
           <td></td>
           <td>MySQL</td>
         </tr>
          <tr>
           <td>Android (Java)</td>
         </tr>
       </tbody>
     </table>
   </div>
   <div id='testimonails' class="intesting-feedback">
     <h2 class="inverse">Interesting things said about me</h2>
     <feedback></feedback>
   </div>

   <div id='projects' class="intresting-projects">
     <h2>Intresting Projects</h2>
     <projects></projects>
   </div>


   <div id='code' class="code-samples">
     <div class="row gutters">
       <div class="col">
        <h2>Code Samples</h2>
        <p>Some people are fan of code samples, if you are one of those guys/gals then you are in for a treat!</p>
        <p>
        <h3>Simple Vue.JS Componenet</h3>
        <a href="https://gist.github.com/mlakkadshaw/6bb6c5bca189076fbe311ce34090a628">View on Github</a>  
        </p>
        <p>
        <h3>Complex Vue.JS Component</h3>
        <a href="https://gist.github.com/mlakkadshaw/469c3282127ef8bcf373ace250f10f66">View on Github</a>
        </p>
        <p>
        <h3>Simple React.JS Component</h3>
        <a href="https://gist.github.com/mlakkadshaw/7d0c9e2061e94ca0afb2af6dba2b393b">View on Github</a>
        </p>
        <p>
        <h3>Complex React.JS Component</h3>
        <a href="https://gist.github.com/mlakkadshaw/84998b5bfaf20c6cf2bf5b04d2a6f554">View on Github</a>
        </p>
       
       </div>
     </div>
   </div>

   <div id='education' class="education">
     <h2>Education</h2>
     <p>
       Formal education is still relevant these days, but don’t worry I got it
covered. I have a Bachelor of Engineering Degree in Computer Technology
and a Diploma in Computer Science and Engineering.
     </p>
     <p>
       <strong>
         Bachelor of Engineering in Computer Techology (2011-2015)
from Nagpur University
       </strong>
     </p>
     <p>
       <strong>
         Diploma in Computer Science and Engineering (2008-2011)
from MSBTE
       </strong>
     </p>
   </div>

   <div id='opensource' class="open-source">
     <h2>Open Source Projects</h2>
     <p>
       I have done a few open source projects, out of them 
Dead Simple Screen Sharing is really popular, Dead Simple Chat ranks on
the first page of Google for the term Open Source Chat.
     </p>
     <div class="row auto gutters">
       <div class="col">
         <a href="https://www.deadsimplescreensharing.com" target="_blank">
         <img src="./assets/deadsimple.jpg" alt="">
         <br />
         <strong>Dead Simple Screen Sharing</strong>
         <ul>
           <li>
             Stars: 188
           </li>
           <li>
             Forks: 79
           </li>
         </ul>
         </a>
       </div>
       <div class="col">
         <a href="http://deadsimplechat.com" target="_blank">
         <img src="./assets/deadsimplechat.jpg" alt="">
         <br />
         <strong>Dead Simple Chat</strong>

         <ul>
           <li>Stars: 106</li>
           <li>Forks: 19</li>
         </ul>
         </a>
       </div>
     </div>
   </div>

   <div id='blogs' class="blog-posts">
     <h2>Technical Blog Posts that I have written</h2>
     <p>
I write blog posts whenever I get the time, but I am not very consistent. Many of my posts have received thousands of views, here is a list of some popular posts.
     </p>
     <ul>
       <li>
         <a target="_blank" href="https://www.mohammedlakkadshaw.com/blog/setup-multi-domain-ssl-node-js-using-letsencrypt-expressgreenlock-express.html/">How to setup multi-domain SSL in Node.JS using letsencrypt-express/greenlock-express</a>
       </li>
       <li>
         <a target="_blank" href="https://www.mohammedlakkadshaw.com/blog/handling-custom-tags-in-android-using-html-taghandler.html/">Handling custom tags in Android using Html.TagHandler()</a>
       </li>
       <li>
         <a target="_blank" href="https://www.mohammedlakkadshaw.com/blog/introduction-to-salisjs.html/">Introduction to SalisJS</a>
       </li>
       <li>
         <a target="_blank" href="https://www.mohammedlakkadshaw.com/blog/using-postgres-with-parse-backend.html/">Using Postgres with Parse Backend</a>
       </li>
       <li>
         <a target="_blank" href="https://www.mohammedlakkadshaw.com/blog/building-command-line-apps-in-node-js.html/">Building command line apps in Node.js</a>
       </li>
       <li>
         <a target="_blank" href="https://www.mohammedlakkadshaw.com/blog/use-your-android-phone-as-a-display-for-raspberrypi.html/">Use your Android Phone as a display for Raspberrypi</a>
       </li>
     </ul>
   </div>

   <div id='faqs' class="faqs">
     <h2>FAQs</h2>
     <p>Here are some the questions I get from people a lot!</p>
     <faq></faq>
   </div>

   <div class="questons">
     <h2 class='inverse' style="margin: 40px;">Any Questions for me? Just ask!</h2>
     <p>
       If you are impressed and want to hire me! then email me at 
<a href="mailto:mohammed.lakkadshaw@gmail.com">mohammed.lakkadshaw@gmail.com</a>, if you are not impressed then man you are
really hard to impress. Feel free to email if you any question, comments
or want further clearification.
     </p>
   </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Projects from './components/Projects'
import Feedback from './components/Feedback'
import Faq from './components/FAQ'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Projects,
    Feedback,
    Faq
  }
}
</script>
<style>
/* html {
  background-color: #F0F4F6;
} */
body {
  max-width: 1440px;
  margin: 0 auto;
  background-color: white;
}

.questons {
  background-color: #262c30;
  padding: 20px;
  	font-size: 15px;
	font-weight: bold;
  	line-height: 2.13;
	text-align: center;
  color: #7f788e;
}

.faqs {
  padding: 20px;
}

.blog-posts {
  padding: 20px;
}
.open-source {
  padding: 20px;
}

.education {
  padding: 20px;
  background-color: #f0f4f6;
}

.intresting-projects {
  	background-color: #f7f5fa;
    padding: 20px;
}

.intesting-feedback {

	border: solid 1px #979797;
  color: #ffffff;
}

.intesting-feedback h2 {
    padding: 20px;
	background-color: #342c3c;
}

.inverse {
  color: #ffffff;  
}

.header, .summary {
  padding: 20px;
}

h1 {
  font-size: 35px;
  margin: 0;
  padding: 0;
  font-family: 'PT Sans', sans-serif;
}

h2 {
  margin: 0;
  padding: 0;
  font-size: 30px;
  font-family: 'PT Sans', sans-serif;
  font-weight: bold;
}

h3 {
  font-family: 'PT Mono', monospace;
}
p, body {
  font-family: 'PT Mono', monospace;
}

.skills-header {
  width: 100%;
	min-height: 102px;
	/* background-image: linear-gradient(to bottom, rgba(128, 113, 113, 0.5), rgba(0, 0, 0, 0.5)); */
  background-image: url('./assets/bg-skills.png');
	border: solid 1px #979797;
  color: white;
  padding: 20px;
}

.skills-header h2 {
  font-size: 25px;
  font-weight: bold;
  font-family: 'PT Sans', sans-serif;
  color: white;
}

table {
  margin-left: 20px;
  font-family: 'PT Sans', sans-serif;
}
table td {
  font-family: 'PT Mono', monospace;
}

.code-samples {
  padding: 20px;
}

.open-source img {
  max-width: 400px;
  border: 7px solid #E8E8E8;
  box-shadow: 0 1px 2px 0 rgba(0,0,0,0.50), 0 1px 1px 0 rgba(0,0,0,0.50);
}

@media only screen and (max-width: 500px) {
  table {
    padding: 0;
    margin: 0;
    font-size: 11px;
  }
}

.nav {
  list-style: none;
  padding: 20px;
  text-align: right;
  font-size: 12px;
}
.nav h3 {
  font-size: 11px;
}
</style>
