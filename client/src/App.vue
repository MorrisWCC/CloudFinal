<template>
  <v-app>
    <Navbar/>
    <Footer/>
  </v-app>
 
</template>

<script>
import Navbar from '@/components/Navbar'
import Footer from '@/components/Footer'
export default {
  name: 'App',

  components: {
   Navbar,
   Footer,
  },

  data: () => ({
    //
  }),
};
</script>
