<script>
import comicsHeader from '../src/components/comicsHeader.vue';
import comicsMain from '../src/components/comicsMain.vue';
import comicsFooter from '../src/components/comicsFooter.vue';



export default {
  name: 'App',
  components: {
    comicsHeader,
    comicsMain,
    comicsFooter,
  }

}
</script>

<template>
<comicsHeader/>
<comicsMain/>
<comicsFooter/>
</template>

<style lang="scss">
@use '../src/styles/general.scss' as *;
</style>
