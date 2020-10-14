
<template>
  <div class="hello">
   <Navbar />
   <h1>ola</h1>
    
  </div>
</template>

<script>
import Navbar from '../../components/Header.vue'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    Navbar
  }
}
</script>

