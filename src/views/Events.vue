<template>
  <div class="login">
        <my-header></my-header>
        <EventsPage :titles="titles"/>
        
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import EventsPage from '@/components/EventsPage.vue'

export default {
  name: 'Events',
  components: {
    'my-header': Header,
    EventsPage
  },
  data(){
    return {
      titles:{
        formTitle:""
      }
    }
  }
}
</script>