<template>
  <Layout>
    <Revenues/>
    <div>
      <div><Icon name="statistics"/>
        <span>统计</span>
      </div>

      <tags/>
    </div>
  </Layout>
</template>

<script lang="ts">
import Revenues from "@/components/Revenues.vue";
import Tags from '@/components/Tags.vue';
export default {
    name: 'Money',
  components:{
      Revenues,
      Tags
    }
  };
</script>
<style lang="scss" scoped>

</style>