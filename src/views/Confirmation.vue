<template>
  <div class="confirmation wrapper">
    <card>
      <div class="content">
        <h1>Thanks for signing up!</h1>
        <p>You'll be the first to find out when this workshop is announced. Stay tuned!</p>
      </div>
      <social-icons />
      <nav>
        <router-link to="/" class="btn">Back to home</router-link>
      </nav>
    </card>
  </div>
</template>

<script>
import Card from '../components/Card.vue';
import SocialIcons from '../components/SocialIcons.vue';

export default {
  name: 'Confirmation',
  components: {
    Card,
    SocialIcons,
  },
};
</script>

<style scoped lang="stylus">
.content, nav
  text-align center

a
  margin 0 auto
  display inline-block
</style>
