<template>
  <nav-header></nav-header>
  <nav-footer></nav-footer>
  <nav-main></nav-main>
</template>

<script>
import { defineComponent } from 'vue'
import NavHeader from '@/components/Header/NavHeader'
import NavFooter from '@/components/Footer/NavFooter'
import NavMain from '@/components/Main/NavMain'
export default defineComponent({
  name: 'Home',  //组件名称
  props: {},  //接收父组件的数据
  compoents: {
    NavHeader,
    NavFooter,
    NavMain
  },  //定义子组件
  //
  setup(props, ctx){
    return {

    }
  }
}) 
</script>

<style lang="scss" scoped>

</style>