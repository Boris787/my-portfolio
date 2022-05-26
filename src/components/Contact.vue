<template>
  <section class="contact-wrap">
    <div class="contact-wrap__text">
      <h2 class="section-header">
        <span>Business inquiries? </span>
        <span>Collaboration?</span>
        <br />
        <span>Or simply want to have a chat with me?</span>
      </h2>
      <button type="button" class="cta-header" id="contactCta">
        <a href="#">Get in touch</a>
      </button>
    </div>
  </section>
</template>

<script></script>

<style scoped>
.contact-wrap {
  background-image: linear-gradient(
      to bottom,
      rgba(0, 0, 0, 0.25),
      rgba(0, 0, 0, 0.2)
    ),
    url(./img/picture-2.jpg);
  background-position: center;
  background-size: cover;
  position: relative;
  min-height: 60vh;
  z-index: 2;
}
.contact-wrap__text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  flex-direction: column;
  align-items: center;
}
.section-header {
  color: #fff;
  font-size: 28px;
  font-weight: 300;
  text-align: center;
  text-transform: uppercase;
  letter-spacing: 2px;
}
span {
  font-weight: bold;
}
.cta-header {
  background: none;
  border: 2px solid #fff;
  border-radius: 50px;
  color: #fff;
  cursor: pointer;
  font-size: 17px;
  font-weight: bold;
  padding: 9px 35px;
  letter-spacing: 2px;
}
a {
  color: #fff;
}
</style>
