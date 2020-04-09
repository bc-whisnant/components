<template>
  <v-app>
    <v-content>
      <BaseInput/>
    </v-content>
  </v-app>
</template>

<script>
import BaseInput from './components/BaseInput';

export default {
  name: 'App',

  components: {
    BaseInput,
  },

  data: () => ({
    //
  }),
};
</script>
