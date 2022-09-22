<template>
    <h1>Menú</h1>
    <hr />
  <card url="https://images.pexels.com/photos/13573666/pexels-photo-13573666.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Vue.js" descripcion="descripcion" precio="$100.00"/> 
  <card url="https://images.pexels.com/photos/13369646/pexels-photo-13369646.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Vue.js" descripcion="descripcion" precio="$150.00"/> 
  <card url="https://images.pexels.com/photos/8463453/pexels-photo-8463453.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Vue.js" descripcion="descripcion" precio="$200.00"/> 
  <card url="https://images.pexels.com/photos/8463464/pexels-photo-8463464.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Vue.js" descripcion="descripcion" precio="$350.00"/> 
  <card url="https://images.pexels.com/photos/315755/pexels-photo-315755.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Vue.js" descripcion="descripcion" precio="$500.00"/> 
  <card url="https://cdn.pixabay.com/photo/2017/11/25/17/17/sandwich-2977251__340.jpg" nombre="Vue.js" descripcion="descripcion" precio="$600.00"/>  
</template>

<script>
  import Card from "./components/Card.vue";
  export default{
    components: { Card },
  };
</script>

