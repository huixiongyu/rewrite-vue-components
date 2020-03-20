<template>
  <div class="home">
    <date-picker />
  </div>
</template>

<script>
// @ is an alias to /src
import DatePicker from '@/components/date-picker/index.vue';

export default {
  name: 'Home',
  components: {
    DatePicker,
  },
};
</script>
