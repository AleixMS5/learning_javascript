<template>
  <div>
    <p>{{counter}}</p>
    <button @click="decrement">Disminuir</button>
    <button @click="increment">Aumentar</button>
  </div>

</template>

<script>

export default  {
  data (){
    return{
    counter: 0
  }

  },
  methods:{
    increment(){
      this.counter++
    },
    decrement(){
      this.counter--
    }
  }
}
</script>