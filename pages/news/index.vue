<template>
  <div>
    <h1>新闻 page</h1>
    <ul>
      <li>
        <nuxt-link :to="{name:'news-id',params:{id:10001,title:'jspang.com'}}">news1</nuxt-link>  
      </li>
      <li>
        <nuxt-link :to="{name:'news-id',params:{id:10002,title:'jspang.com'}}">news2</nuxt-link>  
      </li>
      <li>
        <nuxt-link :to="{name:'index'}">Home</nuxt-link>  
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {

    }
  },
}
</script>
