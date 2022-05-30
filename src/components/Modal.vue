<template>
    <div class="contact-modal" style="border-radius: 10px" v-if="modalOn">
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
        <button type="button" class="send-btn" @click="closeModal">Close</button>
      </form>
    </div>
</template>

<script>
export default {
    name: 'Modal',
    props: {
        showModal: {
            default: false,
        }
    },
    data() {
        return {
            modalOn: false,
        }
    },

    methods: {
        closeModal() {
            this.modalOn = false;
        }
    },

    watch: {
        showModal(val) {
            this.modalOn = val;
        }
    }
}
</script>

<style scoped>
.contact-modal {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 98;
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