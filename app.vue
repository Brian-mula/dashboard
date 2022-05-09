<template>
  <div class="flex">
    <div class=" w-64 bg-blue-500 h-screen">
      <SideNav/>
    </div>
    <div class="flex flex-col w-5/6">
      <MainNav/>
      
       <NuxtPage />
    </div>
   
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'
import SideNav from './components/navigation/sideNav.vue'
import MainNav from './components/navigation/mainNav.vue'


export default defineComponent({
  components: { SideNav, MainNav },
  setup() {
    
  },
})
</script>
