<template>
  <div id="app">

    <header>
      <h3>Subreddits</h3>
    </header>

    <subreddits category="food"></subreddits>
    <subreddits category="sports"></subreddits>
    <subreddits category="space"></subreddits>
    <subreddits category="art"></subreddits>
    <subreddits category="movies"></subreddits>
    <subreddits category="funny"></subreddits>
 
  </div>
</template>

<script>
import Subreddits from './components/Subreddits'

export default {
  name: 'app',
  components: {
    Subreddits
  }
}
</script>

<style>

body {
  font-family: Arial;
  color: #666;
  background: #f4f4f4;
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

header {
  background: coral;
  color: #fff;
  padding: 10px;
  text-align: center;
}

</style>
