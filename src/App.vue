<template>
  <div>
    <SearchBar @termChange="onTermChange"></SearchBar> 
  </div>
</template>

<script>
import SearchBar from './components/SearchBar';

export default {
  name: 'App',
  components: {
    SearchBar
  },
  methods: {
    onTermChange(searchTerm) {
      window.console.log(searchTerm)
    }
  }
}
</script>


// https://coursehunter.net
// :heavy_check_mark:СОХРАНИТЕ его пожалуйста сейчас ,чтоб не потерять :
// логин : Bytebrand19@gmail.com
// пароль: bytebrand2019 (edited)

// lesson 40-70

// router 100

// vuex 70-90