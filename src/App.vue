<template>
  <div>
    <Header />
    <Introduction />
    <Main />
    <Player />
  </div>
  <router-view/>
</template>

<script>
import Header from '@/components/Header'
import Introduction from '@/components/Introduction'
import Main from '@/components/Main'
import Player from '@/components/Player'


export default {
  name: 'App',
  components: { Header,Introduction, Main, Player}
}
</script>

<style>

</style>
