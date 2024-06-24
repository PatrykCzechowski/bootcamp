<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <h1>Siema</h1>
    <br>
    <h2>Licznik: {{ licznik }}</h2>
  
    <button @click="podbij">podbij</button>

  </main>
</template>

<script>
export default{
  data() {
    return {
      licznik: 0
    }
  },
  methods: {
    podbij(){
      this.licznik++;
    }
  },
}
</script>