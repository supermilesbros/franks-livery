<template>
  <section class="contact_one">
    <div class="container">
      <div class="row">
        <div class="col-xl-8">

          <div class="contact_one_form_box">
            <div class="block-title text-left">
              <p>contact with us</p>
              <h3>write us a message</h3>
              <div class="leaf">
                <img src="/assets/images/resources/paddle.png" alt="">
              </div>
            </div>
            <form class="contact_one_form" action="#">
              <div class="row">
                <div class="col-md-6">
                  <div class="input_box">
                    <input type="text" name="name" placeholder="Full name">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input_box">
                    <input type="text" name="email" placeholder="Email Address">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input_box">
                    <input type="text" name="phone" placeholder="Phone">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input_box">
                    <input type="text" name="subject" placeholder="Subject">
                  </div>
                </div>
                <div class="col-md-12">
                  <div class="input_box">
                    <textarea name="message" placeholder="Write Message"></textarea>
                  </div>
                </div>
                <div class="col-md-12">
                  <div class="input_box">
                    <button type="submit" class="thm-btn contact_one_btn">Send Message</button>
                  </div>
                </div>
              </div>
            </form>
          </div>

        </div>

        <div class="col-xl-4">
          <div class="google_map_home5">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2168.570008105876!2d-86.17389472563207!3d39.766124575195846!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x886b50b232bf8c67%3A0x9ba7e83083e863d7!2sWhite%20River%20State%20Park!5e0!3m2!1sen!2sus!4v1674153428198!5m2!1sen!2sus"
              class="google-map__home5" allowfullscreen></iframe>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ContactOne"
    }
</script>

<style scoped>

</style>


