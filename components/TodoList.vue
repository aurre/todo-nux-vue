<template>
<div class="list">
  <b-list-group>
  <b-list-group-item>
     <b-form-checkbox id="checkbox1"
                     v-model="status"
                     value="accepted"
                     unchecked-value="not_completed"
                     class="none">
    Lorem itsum
    </b-form-checkbox>
  </b-list-group-item>
  </b-list-group>
   <!-- <div>State: <strong>{{status}}</strong></div> -->
</div>
</template>

<script>
export default {
  data() {
    return {
      status: 'not_completed',
      class: 'checkbox',
    };
  },
};
</script>


<style scoped>
.list {
  display: flex;
  justify-content: center;
}
.checkbox {
  text-decoration: line-through;
}
</style>
