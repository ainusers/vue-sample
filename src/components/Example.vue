<template>
    <div>
      <van-button type="danger">危险按钮</van-button>
    </div>
</template>
 
<script>
  import {Button} from 'vant'
  export default {
    name: 'VantComponent',
    components:{
      [Button.name]: Button
    }
  }
</script>