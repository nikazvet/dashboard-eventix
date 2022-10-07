<script setup>
import Header from './Header.vue';
import GeneralEventData from './GeneralEventData.vue';
import WeatherReport from './WeatherReport.vue';
import Placeholder from './Placeholder.vue';
import "./assets/main.css";

</script>

<template>
  <div class="grid-container">
    <Header eventname="Event Name"></Header>
    <GeneralEventData date="01-01-2022" time="10:00" location="Strijp-S" eventdescription="description" style="grid-column: span 2"></GeneralEventData>
    <WeatherReport style="grid-column: span 3"></WeatherReport>
    <Placeholder style="grid-column: span 3">00000 tickets sold</Placeholder>
    <Placeholder style="grid-column: span 2">00000 euro made</Placeholder>
    <Placeholder title="amount of tickets bought over time" style="grid-column: span 3"></Placeholder>
    <Placeholder title="gender" style="grid-column: span 2"></Placeholder>
    <Placeholder title="age" style="grid-column: span 3"></Placeholder>
    <Placeholder title="origin of buyers" style="grid-column: span 2"></Placeholder>
    <Placeholder style="grid-column: span 3">refunds</Placeholder>
    <Placeholder style="grid-column: span 2">00000 tickets swapped</Placeholder>
    <Placeholder title="ticket kind distribution(if applicable)" style="grid-column: span 3"></Placeholder>
    <Placeholder title="tickets per order" style="grid-column: span 2"></Placeholder>
    <Placeholder style="grid-column: span 3">000 ticket scanners</Placeholder>
    <Placeholder title="tickets scanned over time" style="grid-column: span 2"></Placeholder>
  </div>
  
</template>

<style scoped>

</style>
