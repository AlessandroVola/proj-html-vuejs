<template>
  <div id="app">
    <!-- header -->
    <HeaderComponent />
    <!-- next conference -->
    <NextConferenceComponent />
    <!-- w questions -->
    <QuestionsComponent />
    <!-- days -->

    <!-- speakers -->

    <!-- program -->

    <!-- map -->

    <!-- location -->

    <!-- recent news -->

    <!-- tickets -->

    <!-- twitter feed -->

    <!-- sponsors -->

    <!-- footer -->
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import NextConferenceComponent from './components/NextConferenceComponent.vue';
import QuestionsComponent from './components/QuestionsComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    NextConferenceComponent,
    QuestionsComponent
  }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
</style>

