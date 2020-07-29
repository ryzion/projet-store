<script>
import presentation from '@/components/presentation.vue';
import '../../src/assets/style.css';
export default {
  name: 'Home',
  components: {
    presentation
  }
}
</script>

<template>
  <div class="home">
      <div class="banner">
        <div class="title">
          <h2>Miam Miam Shop</h2>
        </div>
      </div>
      <presentation />
  </div>
</template>

<style scoped>

.title
{
  font-family: 'Rowdies', cursive;
  font-size: 40px;
  color: #da78da;
  margin-top:50vh;
  position: absolute;
  width:100%;
}

h2 {
  margin: 0;
  text-align: center;
  text-shadow: white 1px 0 15px;
}


</style>
