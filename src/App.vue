<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">

      <nav class="navbar navbar-expand-lg barstyle">
        <div class="container-fluid">
          <div class="logo">
            
          </div>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav">
                <li class="nav-item">
                  <RouterLink class="nav-link active" to="/">Home</RouterLink>
                </li>
                <li class="nav-item">
                  <RouterLink class="nav-link active" to="/">Discord</RouterLink>
                </li>
              </ul>
            </div>
          </div>
</nav>

    </div>
  </header>
  <main>
        
        
    

  </main>
  <RouterView />
</template>

<style scoped>

.barstyle {
  background-color: #f6d06b;
  height: 7.5vh;
}
.logo {
  height: 5vh;
  width: 5vh;
  background-color: #f3e0ac;
  border-radius: 50%;
  display: inline-block;
}

</style>