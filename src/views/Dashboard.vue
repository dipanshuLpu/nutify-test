<template>
    <div>
      <v-alert
        v-model="alert"
        dismissible
        color="cyan"
        border="left"
        elevation="2"
        colored-border
        icon="mdi-twitter"
      >
        You've got <strong>5</strong> new updates on your timeline!.
      </v-alert>
  
      <div class="text-center">
        
      </div>
    </div>
  </template>

<script>
    export default {
      data () {
        return {
          alert: true,
        }
      },
    }
  </script>