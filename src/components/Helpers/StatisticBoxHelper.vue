<template lang="html">

  <div :class="defineSizeSM">
    <article class="statistic-box" :class="color">      
        <slot></slot>    
    </article>
  </div>

</template>

<script lang="js">
  export default  {
    name: 'statistic-box-helper',
    props: ['color', 'sizeColSM'],
    mounted() {

    },
    data() {
      return {

      }
    },
    methods: {

    },
    computed: {
      defineSizeSM(){
        return 'col-sm-' + this.sizeColSM;
      }
    }
}
</script>

<style scoped>
  .statistic-box {
    color: #fff;
  }
</style>
