<template>
  <div class="earning">
    <section class="message"></section>
    <section class="image">
      <img :src="image" alt="" />
    </section>
  </div>
</template>

<script>
import image from "../../sass/avatars/earning.png";
export default {
  data() {
    return {
      image:image
    };
  }
};
</script>

<style lang="sass" src="../../sass/components/Earning.sass" scoped></style>
