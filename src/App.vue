<template>
  <div class="container">
    <h1 class="logo">akbarisanto's ChatApp</h1>
    <ChatForm />
    <ChatMessage />
  </div>
</template>

<script>
import ChatForm from './components/ChatForm.vue';
import ChatMessage from './components/ChatMessage.vue';

export default {
  components: {
    ChatForm,
    ChatMessage,
  },
};
</script>

<style>
@import './style.css';
</style>
