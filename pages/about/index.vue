<template>
  <div>
    <h1>关于 page</h1>
    <ul>
      <li>
        <nuxt-link :to="{name:'index'}">Home</nuxt-link>  
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  transition:'test',
  data() {
    return {

    }
  },
}
</script>
