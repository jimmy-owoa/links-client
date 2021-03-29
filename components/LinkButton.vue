<template>
  <v-card elevation="3" height="60" min-width="480" hover light class="rounded-card" :href="link" target="_blank">
    <v-row>
      <v-col cols="2">
        <v-img
          :src="imgSrc"
          height="40"
          width="40"
          class="ml-4"
        ></v-img>
      </v-col>
      <v-col cols="8">
        <v-flex text-md-center pt-2>{{text}}</v-flex>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {
  props: {
    imgSrc: {
      type: String,
      required: true
    },
    text: {
      type: String,
      required: true
    },
    link: {
      type: String,
      required: false
    }
  }
};
</script>

<style>
</style>