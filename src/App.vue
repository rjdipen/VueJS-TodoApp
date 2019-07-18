<template>
  <v-app>
    <v-toolbar app color="indigo" dark>
      <v-toolbar-title class="headline text-uppercase">
        <span>Todo</span>
        <span class="font-weight-light">App</span>
      </v-toolbar-title>
    </v-toolbar>

    <v-content>
            <todo/>
    </v-content>
  </v-app>
</template>

<script>
import Todo from "./views/Todo";
export default {
  name: 'App',
  components: {
      Todo

  },
  data () {
    return {
      //
    }
  }
}
</script>
