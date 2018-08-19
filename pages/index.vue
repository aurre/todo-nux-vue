<template>
    <div>
      <h1 class="h1"> TO-DO </h1>
      <div>
      <TodoList/>
      </div>
    </div>
</template>

<script>
import TodoList from '@/components/TodoList';

export default {
  components: {
    TodoList,
  },
};
</script>


<style>
.h1 {
  text-align: center;
  margin-top: 2rem;
}
</style>

