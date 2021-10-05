<template>
  <div>
    <Header />
    <Introduction />
    <Main />
    <Player />
    <AuthModal />
  </div>

</template>

<script>
import Header from '@/components/Header'
import Introduction from '@/components/Introduction'
import Main from '@/components/Main'
import Player from '@/components/Player'
import AuthModal from '@/components/AuthModal'


export default {
  name: 'App',
  components: { Header,Introduction, Main, Player, AuthModal}
}
</script>

<style>

</style>
