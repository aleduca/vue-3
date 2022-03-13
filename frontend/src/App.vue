<template>

    <h2 id="my-app">App</h2>

    <p id="teste">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias aliquid cumque debitis dolorem earum eveniet explicabo fugit in inventore iste, magni maiores mollitia obcaecati odit officia repellat suscipit, ut, veritatis.</p>

  <header>
    <div class="wrapper">
      <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/products">Products</router-link>
      </nav>
    </div>
  </header>

  <router-view></router-view>
</template>

<style scoped>
#my-app{
  background-color: aqua;
}

#teste{
  color:red;
}
</style>
