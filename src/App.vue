<template>
  <div id="app">
    <!-- header -->
    <HeaderComponent />
    <!-- next conference -->
    <NextConferenceComponent />
    <!-- w questions -->
    <QuestionsComponent />
    <!-- days -->
    <DaysComponent />
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
import DaysComponent from './components/DaysComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    NextConferenceComponent,
    QuestionsComponent,
    DaysComponent
  }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
</style>

