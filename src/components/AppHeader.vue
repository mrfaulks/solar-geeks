<template>
  <header id="app-header">
    <router-link to="/" class="title-link">
      <h1>The Book List</h1>
    </router-link>  
  </header>
</template>

<style scoped>
#app-header {
  background-color: #DA7422;
  border-bottom: 1px solid #B05F1C;
  color: #FFFBDB;
  font-weight: bold;
  margin-bottom: 1rem;
  padding: 1rem;
  text-align: center;
  text-shadow: 2px 2px #B05F1C;
}
 
#app-header h1 {
  font-size: 1.75rem;
  margin-bottom: 0;
}

.title-link {
  text-decoration: none;
}

.title-link:hover {
  text-decoration: none;
}

.title {
  margin: 0;
  padding: 0;
}
</style>