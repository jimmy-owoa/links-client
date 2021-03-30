<template>
  <v-row justify-sm="center" align-sm="center">
    <v-col cols="12">
      <v-img src="https://jeremiasgutierrez.cl/wp-content/uploads/2021/03/18475845.jpeg" height="100" contain></v-img>
    </v-col>
    <v-col cols="7">
      <link-button imgSrc="https://jeremiasgutierrez.cl/wp-content/uploads/2020/06/favicon.ico" text="SITIO WEB FOTOGRAFÍA" link="https://jeremiasgutierrez.cl"/>
    </v-col>
    <v-col cols="7">
      <link-button imgSrc="https://jeremiasgutierrez.cl/wp-content/uploads/2021/03/instagram.png" text="INSTAGRAM" link="https://www.instagram.com/jg_fotografia__"/>
    </v-col>
    <v-col cols="7">
      <link-button imgSrc="https://jeremiasgutierrez.cl/wp-content/uploads/2021/03/WhatsApp-logo.png" text="WHATSAPP" link="https://wa.me/56951159600"/>
    </v-col>
    <v-col cols="7">
      <link-button imgSrc="https://jeremiasgutierrez.cl/wp-content/uploads/2021/03/1024px-Telegram_2019_Logo.svg.png" text="TELEGRAM" link="https://t.me/jGutierrezA"/>
    </v-col>
    <v-col cols="7">
      <link-button imgSrc="https://jeremiasgutierrez.cl/wp-content/uploads/2021/03/code.png" text="DESARROLLO WEB" link="https://ofalis.cl"/>
    </v-col>
  </v-row>
</template>

<script>
import LinkButton from '~/components/LinkButton.vue';

export default {
  components: {
    LinkButton
  },
};
</script>,

<style scoped>
.rounded-card{
    border-radius: 50px;
}
</style>