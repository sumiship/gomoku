<template>
  <div class="home">
    <Header/>
    <Field />
    <Footer/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Field from '@/components/Field.vue';
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';

@Component({
  components: {
    Field,
    Header,
    Footer
  },
})
export default class Home extends Vue {}
</script>
<style>
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}
</style>

