<template>
  <div class="landing">
    <section class="message">
      <p class="message-title">
        Earn freebies with your active social media account!
      </p>
      <p class="message-text">
        Become a Mini-Social Influencer
      </p>
      <b-button variant="danger">Sign Up</b-button>
    </section>
      <section class="image">
        <img :src="image" />
    </section>  
  </div>
</template>

<script>
import image from '../../sass/avatars/landing.png'
export default {
   data: function() {
    return {
      image: image
    };
  }
}
</script>

<style src='../../sass/components/Landing.sass' scoped lang='sass'>

</style>