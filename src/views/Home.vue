<template>
  <div class="home">
    <h1>This is home page</h1>
    <MessageDisplay />
  </div>
</template>

<script>
import MessageDisplay from '@/components/MessageDisplay.vue';

export default {
  name: 'home',

  components: {
    MessageDisplay,
  },
};
</script>
