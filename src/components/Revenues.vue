<template>
  <div class="box-header">
    <div id="left" :class="num===1?'active':''" @click="num=1">支出</div>
    <div id="right" :class="num===2?'active':''" @click="num=2">收入</div>
  </div>
</template>

<script lang="ts">
export default {
  name: "Revenues",
  data(){
    return{
      num:1
    }
  }
};
</script>

<style lang="scss" scoped>

.box-header {
  display: flex;
  justify-content:center;
  text-align: center;
  background-color: #e8e8e8;
  padding-top: 18px;


  div{
    font-size:20px;
    padding-bottom: 3px;
  }
  #left{
    margin-right: 10px;
  }
}
.active{
  border-bottom: 2px solid black;
}

</style>