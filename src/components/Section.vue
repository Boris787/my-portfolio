<template>
  <section class="autob-wrap">
    <h3 class="generic-header">"Building With Passion"</h3>
    <p class="autob-wrap__text">
      Everything I build, I tend to build with passion. With more than 4 years
      of experience in web development industry I learned to write scalable,
      flexible, reusable and elegant code. Over the course of years I was
      learning "on go". While working for multiple clients on multiple projects
      I faced many challenges, whole lot of problems were thrown at me that I
      had to solve. This exact firestorm of projects and challenges is the
      reason I learned a lot.
    </p>
    <h3 class="autob-wrap__exp-text">Experienced With</h3>
    <div class="autob-wrap__exp">
      <div class="autob-wrap__exp__block">
        <h4>HTML ↓</h4>
        <span>Optimizing SEO. Methodologies, Writing clean markup...</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>CSS ↓</h4>
        <span>Writing clean and straightforward code, Frameworks...</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>SASS / SCSS ↓</h4>
        <span
          >BEM Methodology, Clean nesting, Mixins, Reusable Components..</span
        >
      </div>
      <div class="autob-wrap__exp__block">
        <h4>JavaScript ↓</h4>
        <span
          >JS Next, AJAX, Pardigms (OOP / FP), ES6+ Syntax, API
          Integrations...</span
        >
      </div>
      <div class="autob-wrap__exp__block">
        <h4>VueJS ↓</h4>
        <span
          >Fast & Lightweight Code, Components, Vuex + NuxtJS, SPA &
          PWA...</span
        >
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.autob-wrap {
  text-align: center;
  min-height: 80vh;
  margin: 0 50px;
  margin-top: 50px;
  margin-bottom: 50px;
}
.generic-header {
  font-size: 26px;
  text-transform: uppercase;
  letter-spacing: 5px;
  text-align: center;
}
.autob-wrap__text {
  font-size: 20px;
  word-spacing: 2px;
}
.autob-wrap__exp-text {
  font-size: 22px;
  margin-top: 50px;
  text-transform: uppercase;
  letter-spacing: 5px;
}
.section-wrap__experience {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}
.section-wrap__exp__block {
  display: flex;
  align-items: center;
  margin: 0 25px;
}
h4 {
  font-size: 20px;
}
span {
  font-size: 20px;
}
</style>
