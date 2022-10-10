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
    <SpeakersComponent />
    <!-- program -->
    <ProgramComponent />
    <!-- map -->
    <MapComponent />
    <!-- location -->
    <LocationComponent />
    <!-- recent news -->
    <RecentNewsComponent />
    <!-- tickets -->
    <TicketsComponent />
    <!-- twitter feed -->
    <TwitterComponent />
    <!-- sponsors -->

    <!-- footer -->
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import NextConferenceComponent from './components/NextConferenceComponent.vue';
import QuestionsComponent from './components/QuestionsComponent.vue';
import DaysComponent from './components/DaysComponent.vue';
import SpeakersComponent from './components/SpeakersComponent.vue';
import ProgramComponent from './components/ProgramComponent.vue';
import MapComponent from './components/MapComponent.vue';
import LocationComponent from './components/LocationComponent.vue';
import RecentNewsComponent from './components/RecentNewsComponent.vue'
import TicketsComponent from './components/TicketsComponent.vue';
import TwitterComponent from './components/TwitterComponent.vue';


export default {
  name: 'App',
  components: {
    HeaderComponent,
    NextConferenceComponent,
    QuestionsComponent,
    DaysComponent,
    SpeakersComponent,
    ProgramComponent,
    MapComponent,
    LocationComponent,
    RecentNewsComponent,
    TicketsComponent,
    TwitterComponent
  }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
</style>

