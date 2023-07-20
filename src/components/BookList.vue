<template>
  <div id="card-container">
    <BookCard v-for="book of bookList" :key="book.id" :book="book" />
  </div>
</template>

<script>
import BookCard from "./BookCard.vue"

export default {
  components: {
    BookCard
  },

  props: ['bookList']
}
</script>

<style scoped>
#card-container {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: space-around;
}
</style>