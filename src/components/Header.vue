<script>
//import
import Header from './components/Header.vue';

//export
export default {
  components: {
    Header,
  },


}
</script>

<template></template>

<style lengs="scss">
/* regole base  */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin: auto;
}

.flex {
  display: flex;
}

.wrap {
  flex-wrap: wrap;
}

img {
  max-width: 100%;
}

ul {
  list-style-type: none;
}

ul li {
  margin: 0.5rem;
}

ul li a {
  color: inherit;
  text-decoration: none;
}
</style>