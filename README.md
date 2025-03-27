<style>
.readme-container {
  position: relative;
  padding: 20px;
  animation: fadeIn 2s;
}

.glow-light {
  position: absolute;
  top: 0;
  left: 0;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background: radial-gradient(circle, var(--glow-color), transparent);
  box-shadow: 0 0 10px var(--glow-color), 0 0 20px var(--glow-color);
  animation: move-around 10s infinite linear;
}

@keyframes move-around {
  0% { transform: translate(0, 0); }
  25% { transform: translate(100%, 0); }
  50% { transform: translate(100%, 100%); }
  75% { transform: translate(0, 100%); }
  100% { transform: translate(0, 0); }
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.icon-wrapper {
  display: inline-block;
  transition: transform 0.3s, filter 0.3s;
}

.icon-wrapper:hover {
  transform: scale(1.2);
  filter: drop-shadow(0 0 5px var(--glow-color));
}

html[data-color-mode="light"] {
  --glow-color: #3498db; /* Blue glow for light mode */
}

html[data-color-mode="dark"] {
  --glow-color: #5dade2; /* Cyan glow for dark mode */
}
</style>

<div class="readme-container">

<img align="right" alt="Coding" width="400" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">

<h1 align="center">Hi 👋, I'm Paul Ojo</h1>

<h3 align="center">I am a passionate Software Engineer with strong background in Backend and Frontend development, skilled at implementing efficient, scalable, and reliable software solutions that meet the needs of users. I have a passion for solving complex problems and a commitment to staying up-to-date with the latest trends and technologies in the field.</h3>

- 👨‍💻 Here is my portfolio link [https://paul-ojo-portfolio.vercel.app](https://paul-ojo-portfolio.vercel.app/)
- 💬 Ask me about **Nodejs, Nextjs, Reactjs, JavaScript, and more related stuff**
- ⚡ Fun fact **I like to stay up-to-date with the latest trends and techniques**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a class="icon-wrapper" href="https://twitter.com/paulojo321" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="paulojo321" height="30" width="40" /></a>
<a class="icon-wrapper" href="https://linkedin.com/in/paul ojo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="paul ojo" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left">
<a class="icon-wrapper" href="https://www.chartjs.org" target="_blank" rel="noreferrer"><img src="https://www.chartjs.org/media/logo-title.svg" alt="chartjs" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://expressjs.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://firebase.google.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://www.w3.org/html/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://jestjs.io" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://nextjs.org/" target="_blank" rel="noreferrer"><img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://www.nginx.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a>
<a class="icon-wrapper" href="https://reactnative.dev/" target="_blank" rel="noreferrer"><img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/></a>
</p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=tosinkoa&show_icons=true&locale=en&layout=compact" alt="tosinkoa" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=tosinkoa&show_icons=true&locale=en" alt="tosinkoa" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=tosinkoa&" alt="tosinkoa" /></p>

<div class="glow-light"></div>

</div>
