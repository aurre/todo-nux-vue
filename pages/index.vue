<template>
    <div>
      <navbar></navbar>
      <h1 class="h1"> TO-DO </h1>
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  components: {
    Navbar,
  },
};
</script>

<style>
.h1 {
  text-align: center;
  margin-top: 2rem;
}
</style>

