<template>
  <div class="main-container">
    <h1>Gerenciar Pedidos 
      <Dashborad />
    </h1>
    
  </div>
  
</template>


<script>
import Dashboard from "../components/Dashborad.vue";

export default {
  name: "Pedidos",
  components: {
    Dashboard,
  },
};
</script>

