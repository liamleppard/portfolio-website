<template>
  <div class="container">
    <div class="presentation-div">
      <div>
        <p class="title">My name is Liam Leppard.</p>
        <p class="subtitle">I am a Full Stack Developer from Kelowna, British Columbia, Canada.</p>
        <p class="subtitle">
          Feel free to drop me an email at
          <a href="mailto:***@***..com">***@***.com</a>
        </p>
      </div>
    </div>
    <div class="projects">
      Permanence of the stars trillion quis nostrum exercitationem ullam corporis suscipit laboriosam billions upon billions explorations science. Drake Equation consectetur rich in mystery totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo from which we spring dispassionate extraterrestrial observer. Network of wormholes courage of our questions invent the universe Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur Sea of Tranquility sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt and billions upon billions upon billions upon billions upon billions upon billions upon billions.
    </div>
    <div class="skills">
      Of brilliant syntheses prime number billions upon billions Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur birth emerged into consciousness? At the edge of forever Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur consectetur realm of the galaxies extraordinary claims require extraordinary evidence sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt and billions upon billions upon billions upon billions upon billions upon billions upon billions.
    </div>
    <div class="footer">
      Radio telescope cosmic ocean bits of moving fluff light years tesseract extraordinary claims require extraordinary evidence. Something incredible is waiting to be known qui dolorem ipsum quia dolor sit amet the sky calls to us consectetur permanence of the stars dream of the mind's eye? Nisi ut aliquid ex ea commodi consequatur made in the interiors of collapsing stars take root and flourish Rig Veda dispassionate extraterrestrial observer courage of our questions and billions upon billions upon billions upon billions upon billions upon billions upon billions.
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
  min-height: 50vh;
  display: flex;
  align-items: center;
  line-height: 2rem;
  animation-name: topFadeIn;
  animation-duration: 0.75s;
}

.title {
  font-size: 2rem;
  font-weight: 700;
}

.subtitle {
  font-weight: 300;
  font-size: 1.2rem;
}

.projects, .skills {
  margin: 5rem 0;
}

.footer {
  width: 100%;
}

@keyframes topFadeIn {
  0% {
    transform: translateY(10%);
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
    min-height: 100vh;
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
