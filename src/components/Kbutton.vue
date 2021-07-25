

<!--
  *
  * Template
  *
  -->
<template>
  <div>
    <button @click="fire">Click Korver Button!</button>
  </div>
</template>


<!--
  *
  * Style
  *
  -->
<style scoped>
button {
  background-color: #fff;
  color: #41B883;
  border-radius: 15px;
  padding: 10px;
  border: 1px solid #41B883;
  transition: all .3s;
}
button:hover {
  cursor: pointer;
  background-color: #35495E;
  border: 1px solid #35495E;
}
</style>


<!--
  *
  * Script
  *
  -->
<script>

  // Component
  export default {


    /**
     *
     * Component Name
     *
     */
    name: 'k-button',


    /**
     *
     * Inner Components
     *
     */
    components: {
    },


    /**
     *
     * Props
     *
     */
    props: [],


    /**
     *
     * Data
     *
     */
    data () {
      return {
      }
    },


    /**
     *
     * Computed
     *
     */
    computed: {
    },


    /**
     *
     * Methods
     *
     */
    methods: {


      /**
       *
       * Click Button
       *
       */
      fire () {
        alert ('Button Clicked!');
      },
    }
  }
</script>
