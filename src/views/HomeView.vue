<template>
  <div class="home">
    <Nav />
    <Chat />
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from '@/components/Nav.vue'
import Chat from '@/components/Chat.vue'

export default {
  name: 'HomeView',
  components: { Nav, Chat }
}
</script>
