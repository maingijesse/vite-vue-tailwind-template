<template>
  <div class="container p-5 mx-auto">
    <h1 class="text-center text-3xl font-semibold text-green-600 mb-5">
      About Page
    </h1>
    <p class="tracking-wider">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iste illo sit
      error et quae id sapiente assumenda, quisquam expedita quam quo laborum
      totam optio dolore fugit atque corporis, natus tempora, voluptatum eos
      voluptatem vel nemo labore. Id nobis ipsum nesciunt, cupiditate sapiente
      dolores sed doloremque ducimus expedita dolor aliquam tenetur.
    </p>
    <p class="text-indigo-700 tracking-normal text-3xl">
      Vuex in Vue3: Testing Store Variable :
      <span class="underline">
        {{ name }}
      </span>
      is a variable in vuex store.
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: this.$store.state.name,
    }
  },
}
</script>
