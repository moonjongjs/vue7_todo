<template>
  <div id="app">
      <header-component></header-component>
      <input-component></input-component>
      <list-component></list-component>
      <footer-component></footer-component>      
  </div>
</template>

<script>
//외부컴포넌트 등록하기
import HeaderComponent from './components/HeaderComponent.vue'
import InputComponent from './components/InputComponent.vue'
import ListComponent from './components/ListComponent.vue'
import FooterComponent from './components/FooterComponent.vue'


export default {
    name: 'app',
    data() {
        return{
            title:''
        }
    },
    components: {
        'header-component': HeaderComponent,
        'input-component': InputComponent,
        'list-component': ListComponent,
        'footer-component': FooterComponent
    }


}
</script>

<style>
    
</style>