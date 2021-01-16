<template>
  <div class="home">
    <img class="homepageLogo" src ="https://i.pinimg.com/originals/77/0b/80/770b805d5c99c7931366c2e84e88f251.png"/>
    <SearchBar/>
    <DayForecastTab/>
    <Weather/>
  </div>
</template>

<script>
import Weather from '@/components/Weather.vue'
import SearchBar from '@/components/SearchBar.vue'
import DayForecastTab from '@/components/DayForecastTab.vue'

export default {
  name: 'home', 
  components: { 
    Weather,
    SearchBar,
    DayForecastTab
  },
  mounted(){
  }
}
</script>
<style scoped lang="scss">
.homepageLogo {
  padding-top: 1%;
  width: 12%;
}
</style>

