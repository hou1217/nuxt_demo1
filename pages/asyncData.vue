<template>
  <div>
    <h2>姓名：{{info.name}}</h2>
    <h2>年龄：{{info.age}}</h2>
  </div>
</template>
<script>
import axios from 'axios'
export default {
  data() {
    return {
      name:'hello World',
    }
  },
  async asyncData(){
    let {data}= await axios.get('https://api.myjson.com/bins/clhko')
    return {info: data}

  }
  
}
</script>

