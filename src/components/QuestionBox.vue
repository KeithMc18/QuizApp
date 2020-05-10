<template>
  <div>
    <b-jumbotron lead="Bootstrap v4 Components for Vue.js 2">
      <template v-slot:lead>
        {{currentquestion.question}}
      </template>

      <hr class="my-4">

      <p>
       Answers
      </p> 

      <b-button variant="primary" href="#">Submit</b-button>
      <b-button variant="success" href="#">Next</b-button>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  props: {
    currentquestion: Object
  }
}
</script>>