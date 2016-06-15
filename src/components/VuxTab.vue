<template>
    <tab>
        <tab-item :selected="demo1 === '已发货'" @click="demo1 = '已发货'">已发货</tab-item>
        <tab-item :selected="demo1 === '未发货'" @click="demo1 = '未发货'">未发货</tab-item>
        <tab-item :selected="demo1 === '全部订单'" @click="demo1 = '全部订单'">全部订单</tab-item>
    </tab>

</template>

<script>
import {Tab, TabItem} from 'vux-components/tab'

export default {
  components: {Tab, TabItem},
  data () {
    return {
      demo1: '未发货'
    }
  }
}
</script>

<style>
</style>
