<template>
       <v-app id="app" dark standalone>
        <v-toolbar fixed dark>
            <v-toolbar-title class="orange--text">The Feeling</v-toolbar-title>
        </v-toolbar>
        <main>
            <v-container fluid>
               <router-view></router-view>
            </v-container>
        </main>
         <v-footer class="pa-5">
      <span class="orange--text">© {{ new Date().getFullYear() }} aofdev</span>
    </v-footer>
    </v-app>
</template>

<script>
export default {

}
</script>

<style>
body{
  font-family: 'Prompt', sans-serif;
}
</style>
