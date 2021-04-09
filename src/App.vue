<template>
  <div id="app">
    <BiubiuComponent>
      <biubiu-banner :obj="{
        src: 'https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a2e81c9d78a24c5fb0cb33bfcc366dce~tplv-k3u1fbpfcp-watermark.image',
        link: 'https://www.baidu.com',
      }" />
      <biubiu-form />
    </BiubiuComponent>
  </div>
</template>

<script>
import BiubiuComponent from './common/biubiu-component';
import BiubiuBanner from './components/biubiu-banner/index';
import BiubiuForm from './components/biubiu-form/index';
export default {
  name: 'App',
  components: {
    BiubiuBanner,
    BiubiuForm,
    BiubiuComponent,
  }
}
</script>
