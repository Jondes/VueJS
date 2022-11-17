<template>
  <div>
    <h2>Vue Js Dropdown Get Selected Value</h2>
    <select name="cars_id" @change="onChange($event)" class="form-select form-control">
        <option>---- Select Car ----</option>
        <option value="sonata_hybrid">Sonata Hybrid</option>
        <option value="odyssey">Odyssey</option>
        <option value="ford_mustang">Ford Mustang</option>
        <option value="tesla_model">Tesla Model 3</option>
        <option value="honda_accord">Honda Accord</option>
        <option value="ford_expedition">Ford Expedition</option>
        <option value="lincoln_navigator">Lincoln Navigator</option>
    </select>
  
  </div>
</template>
 
<script>
export default {
  name: "App",
  data() {
    return {
         onChange(e) {
              console.log(e.target.value);
          }
    };
  }
};
</script>