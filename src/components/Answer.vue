<template>
  <div class="alert alert-success text-center">
      <h1>Chính xác!</h1>
      <hr>
      <button class="btn btn-primary" @click="onNextQuestion">Next Question</button>
  </div>
</template>

<script>
  export default {
    methods:{
      onNextQuestion(){
        this.$emit('confirmed');
      }
    }
  }
</script>

<style>

</style>
