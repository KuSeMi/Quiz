<script setup>
  import { defineProps } from "vue";
  import { RouterLink } from "vue-router";


  const {numberOfCorrectAnswers, quizQustionLength} = defineProps(['quizQustionLength', 'numberOfCorrectAnswers'])
</script>

<template>
  <div class="results">
    <p>Your Results...</p>
    <h1>{{ numberOfCorrectAnswers }}/{{ quizQustionLength }}</h1>
    <RouterLink to="/" class="go-back-button">Go Back</RouterLink>
  </div>
</template>

<style scoped>
  .results {
    text-align: center;
    padding: 100px 0;
  }

  p {
    font-size: 25px;
  }

  h1 {
    font-size: 80px;
  }

  .go-back-button {
    margin-top: 20px;
    padding: 15px 35px;
    font-size: 25px;
    background-color: bisque;
    border: none;
    color: black;
    text-decoration: none;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
  }
</style>