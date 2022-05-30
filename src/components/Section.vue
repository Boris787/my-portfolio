<template>
  <section class="autob-wrap">
    <h3 class="generic-header">"This is me ↓"</h3>
    <p class="autob-wrap__text">
      I am a Junior Front-End developer who has a lot of ambition for work. I
      have been in these rivers for 2 years, during that period I learned a lot
      about this business. I am ready to sit for the junior position, but also
      to move away from it to a higher position very quickly by progressing,
      learning, practicing.
    </p>
    <h3 class="autob-wrap__exp-text">EXPERIENCED WITH</h3>
    <div class="autob-wrap__exp">
      <div class="autob-wrap__exp__block">
        <h4>HTML →</h4>
        <span>Tu mu dodje neki tekst</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>CSS →</h4>
        <span>Writing clean and straightforward code</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>SASS / SCSS →</h4>
        <span>Tu mu dodje neki tekst</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>JavaScript →</h4>
        <span>Tu mu dodje neki tekst </span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>VueJS →</h4>
        <span>Tu mu dodje neki tekst</span>
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
.autob-wrap__exp__block {
  display: flex;
  align-items: center;
  margin: 0 25px;
}
h4 {
  font-size: 20px;
  margin-right: 10px;
}
span {
  font-size: 17px;
}
</style>
