<template>
    <h1>{{message}}</h1>
</template>

      <script>
              export default  {
                  data(){
                      return{
                          message :"Hello World"
                      }
                  }
              }
      </script>


<style scoped>
    h1{
      color: aqua;
      text-justify: center;
      font-size: 50px;
    }
</style>