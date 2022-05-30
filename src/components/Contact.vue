<template>
  <section class="contact-wrap">
    <div class="contact-modal" style="border-radius: 10px">
      <form action="https://formspree.io/f/xeqnnpek" method="POST">
        <div>
          <span>Message</span>
        </div>
        <div class="contact-modal__input-field">
          <input type="text" placeholder="Name" name="Name" />
        </div>
        <div class="contact-modal__input-field">
          <input type="text" placeholder="Phone No." name="Phone" />
        </div>
        <div class="contact-modal__input-field">
          <input type="text" placeholder="Email Address" name="Email" />
        </div>
        <div class="contact-modal__input-field">
          <textarea name="Message" placeholder="Message" rows="10"></textarea>
        </div>
        <input type="submit" value="Submit" class="send-btn" />
        <button type="button" class="send-btn">Close</button>
      </form>
    </div>
    <div class="contact-wrap__text">
      <h2 class="section-header">
        <span>Questions? </span>
        <span>Explanations?</span>
        <br />
        <span>The Business?</span>
        <br />
        <span>Feel free to contact me!</span>
      </h2>
      <button type="button" class="cta-header" id="contactCta">
        It's free, get in touch
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
.contact-modal {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 98;
  /* display: none; */
}
form {
  background: #fff;
  width: 500px;
  padding: 30px;
  font-size: 18px;
  border-radius: 10px;
}
form input,
textarea {
  width: 100%;
  margin: 5px;
  border-top: none;
  border-left: none;
  border-right: none;
  border-bottom: 1px solid #000;
  outline: none;
}
#input-field {
  padding-bottom: 20px;
  display: flex;
  align-items: center;
}
#input-field {
  font-size: 22px;
  margin-right: 15px;
}
.send-btn {
  width: 100px;
  border: none;
  background: #000;
  color: #fff;
  font-size: 16px;
  padding: 6px 0;
  border-radius: 50px;
  cursor: pointer;
}
</style>
