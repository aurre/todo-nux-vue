<template>
  <div>
    <h1>Hello Features</h1>
    <jumbo title="Superjumbo for features"></jumbo>
    <order-detail orderNumber="333"></order-detail>

  </div>
</template>

<script>
import Jumbo from '@/components/Jumbo.vue';
import OrderDetail from '@/components/OrderDetail.vue';

export default {
  components: {
    Jumbo,
    OrderDetail,
  },
};
</script>
