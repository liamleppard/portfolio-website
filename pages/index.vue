<template>
  <div class="container">
    <div class="header">
      <h2>Liam Leppard</h2>
      <div>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#footer">Contact</a>
        <button class="nightmode-toggle">
          🌑
        </button>
      </div>
    </div>
    <div class="presentation-div">
      <div class="presentation-text">
        <h1 class="title">
          My name is Liam Leppard.
        </h1>
        <span class="subtitle">I am a Full Stack Developer from Kelowna, British Columbia, Canada.</span>
        <span class="subtitle">
          Feel free to drop me an email at
          <a href="mailto:***@***..com">***@***.com</a>
        </span>
      </div>
    </div>
    <div id="projects" class="projects">
      <h2>Projects</h2>Permanence of the stars trillion quis nostrum exercitationem ullam corporis suscipit laboriosam billions upon billions explorations science. Drake Equation consectetur rich in mystery totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo from which we spring dispassionate extraterrestrial observer. Network of wormholes courage of our questions invent the universe Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur Sea of Tranquility sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt and billions upon billions upon billions upon billions upon billions upon billions upon billions.
    </div>
    <div id="skills" class="skills">
      <h2>Skills</h2>Of brilliant syntheses prime number billions upon billions Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur birth emerged into consciousness? At the edge of forever Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur consectetur realm of the galaxies extraordinary claims require extraordinary evidence sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt and billions upon billions upon billions upon billions upon billions upon billions upon billions.
    </div>
    <div id="footer" class="footer">
      <h2>Contact</h2>
      <div class="contacts">
        <a href="mailto:***@***..com">***@***.com</a>
        <span>github</span>
        <span>linkedin</span>
      </div>
    </div>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  width: 100%;
  padding: 0 10px;
}

.presentation-div {
  min-height: 40vh;
  display: flex;
  align-items: center;
  line-height: 2rem;
  animation-name: topFadeIn;
  animation-duration: 0.75s;
}

.presentation-text {
  display: flex;
  flex-direction: column;
}

.title {
  font-size: 2rem;
  font-weight: 700;
}

.subtitle {
  font-size: 1.4rem;
}

.projects,
.skills,
.footer {
  margin-bottom: 5rem;
}

.contacts {
  display: flex;
  flex-direction: column;
}

.nightmode-toggle {
  border-style: unset;
  background: transparent;
  cursor: pointer;
}

.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 10vh;
}

@keyframes topFadeIn {
  0% {
    transform: translateY(5%);
    opacity: 0;
  }

  100% {
    transform: translateY(0);
    opacity: 1;
  }
}

@media (min-width: 576px) {
  .container {
    max-width: 540px;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 720px;
  }

  .presentation-div {
    min-height: 90vh;
  }
}

@media (min-width: 992px) {
  .container {
    max-width: 960px;
  }
}

@media (min-width: 1200px) {
  .container {
    max-width: 1140px;
  }
}
</style>
