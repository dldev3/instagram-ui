<template>
  <div id="app">
   <Notification />
   <Header />
   <Stories />
   <UserContent />
   <Navigation />
  </div>
</template>

<script>
import Notification from './components/android/Notification';
import Header from './components/Header';
import Stories from './components/Stories';
import UserContent from './components/UserContent';
import Navigation from './components/Navigation';

export default {
  components: {
   Notification,
   Header,
   Stories,
   UserContent,
   Navigation
  }
}
</script>

<style>

</style>
