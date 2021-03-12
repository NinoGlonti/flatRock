<template>
  <div class="header">
    <h3>Project Access</h3>
    <input type='text' placeholder= 'Type to filter the table'>
  </div>
</template>

<script>
export default {
  name: 'Header'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- scoped is adding style only for the component, it's not global-->
<style scoped>
  .header {
    display: flex;
    justify-content: space-between;
    margin: 4em;
    background-color: #ffffff;
    box-shadow: 0 4px 2px -2px silver;
    
  }
  input {
  outline: 0;
  border-width: 0 0 2px;
  border-bottom: 1px solid silver;
  padding: 0;
  width: 20vw;
  
  }

</style>
