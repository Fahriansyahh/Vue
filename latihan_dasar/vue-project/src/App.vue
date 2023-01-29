<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import mainn from './components/main.vue'
import asd from './components/asd.vue'

</script>

<template>
  <header>
    <h1>vueJS</h1>
    <ul>
      <li>home</li>
      <li>about</li>
      <li>contact</li>
    </ul>
  </header>
  <main>
    <div class="image"> <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    </div>
    <asd nama="asdaadasdsa"/>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus cum beatae vero maiores accusamus, impedit
      eligendi adipisci reprehenderit exercitationem at nemo labore molestias blanditiis dolorem pariatur asperiores
      odio repellat quaerat! Lorem ipsum dolor sit, amet consectetur adipisicing elit. Veniam dolore enim unde ullam
      necessitatibus quia voluptatem labore, sapiente quibusdam doloribus libero at suscipit dolor blanditiis
      consectetur explicabo praesentium optio. Dolor.</p>
    <mainn name="muhammad fahriansyah" />
  </main>
</template>

<style scoped>
header {
  top: 0px;
  margin: 0px;
  width: 100%;
  padding: 5px;
  background-color: rgb(21, 244, 21);
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-content: center;
  align-items: center;
}

h1 {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

ul {
  display: flex;
  gap: 10px;
  justify-content: end;
  padding: 10px;
}

ul li {
  list-style: none;
}

main {
  width: 100%;
  display: grid;
  grid-template-columns: 1fr;
  justify-items: center;
  background-color: hotpink;
  align-items: center;
}
</style>
