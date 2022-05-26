<template>
  <header class="header-wrap">
    <div class="header-wrap__container">
      <h3>"Boris | DEV"</h3>
      <h1>Juinor Front-End Developer</h1>
      <div class="header-wrap__container__content">
        <span>VueJS |</span>
        <span>JavaScript |</span>
        <span>HTML |</span>
        <span>More</span>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {},
};
</script>

<style scoped>
.header-wrap {
  margin: 0;
  padding: 0;
  border: 0;
  height: 100vh;
  background-image: linear-gradient(
      to bottom,
      rgba(0, 0, 0, 0.62),
      rgba(0, 0, 0, 0.73)
    ),
    url(./img/picture.jpg);
  background-position: center;
  background-size: cover;
  position: relative;
}
.header-wrap__container {
  color: #fff;
  position: absolute;
  top: 45%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-transform: uppercase;
  text-align: center;
  width: 100%;
}
h3 {
  font-size: 22px;
  font-weight: lighter;
  letter-spacing: 8px;
  color: #999999;
}
h1 {
  font-size: 45px;
  letter-spacing: 15px;
  color: #999999;
}
.header-wrap__container__content {
  display: flex;
  justify-content: center;
  margin-bottom: 40px;
}
span {
  font-size: 15px;
  margin-right: 5px;
  letter-spacing: 5px;
}
</style>
