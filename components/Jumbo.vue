<template>
  <div>
    <h1>{{ title }}</h1>
  <b-jumbotron header="Bootstrap Vue" lead="Bootstrap 4 Components for Vue.js 2" >
  <p>For more information visit website</p>
  <b-btn variant="primary" href="/">Go to home page</b-btn>
  </b-jumbotron>
  </div>
</template>

<script>
export default {
  props: ['title'],
};
</script>

