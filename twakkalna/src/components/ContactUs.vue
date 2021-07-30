<template>
  <div class="row">
    <h1>تواصل معنا</h1>
  </div>
  <div class="row">
    <div class="offset-7 col-5 contact-details mt-5">
      <div>
        <span class="mx-1">8001289999</span>
        <span
          ><img class="icon" src="../assets/phone.png" alt="phone icon"
        /></span>
      </div>
      <div>
        <span class="mx-1">TawakkalnaApp@</span>
        <span
          ><img class="icon" src="../assets/twitter.png" alt="twitter icon"
        /></span>
      </div>
      <div>
        <span class="mx-1">contact@tawakkalna.gov.sa</span>
        <span
          ><img class="mail" src="../assets/mail.png" alt="mail icon"
        /></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactUs",
};
</script>

<style>
    .contact-details {
        background-color: green;
        text-align: right;
        padding-top: 20px;
        padding-bottom: 20px;
        border-start-start-radius: 5em 5em;
        border-end-start-radius: 5em 5em;
        color: white;
    }

    .icon {
        width: 40px;
    }

    .mail {
        width: 32px;
        margin-right: 3px;
        margin-left: 5px;
    }
</style>