<template>
  <form class="bg-green-500 rounded mx-auto px-6 py-6 w-1/2">
    <div class="flex flex-col mt-3" v-if="errors">
      <span class="text-red-200 italic"></span>
    </div>
    <div class="flex flex-col mt-3">
      <label for="email" class="text-white text-xl">Email</label>
      <input type="email" class="px-2 py-1 rounded" placeholder="Email">
    </div>
    <div class="flex flex-col mt-3">
      <label for="password" class="text-white text-xl">Password</label>
      <input type="password" class="px-2 py-1 rounded" placeholder="Password">
    </div>
    <div class="flex items-baseline justify-between mt-3">
      <button type="button"
              class="inline-flex items-center justify-center px-4 py-2 bg-teal-300 border border-transparent rounded-md font-semibold text-teal-700 uppercase tracking-widest hover:bg-green-700 hover:text-gray-200 focus:outline-none focus:border-blue-700 focus:shadow-outline-blue active:bg-teal-300 transition ease-in-out duration-150">
        Login
      </button>
      <div>
        Don't have an account?
        <NuxtLink to="/auth/register" class="text-sm text-white hover:underline hover:text-green-200">
          Register
        </NuxtLink>
      </div>
    </div>
  </form>
</template>

<script>
export default {
  name: "login",
  layout: 'guest'

}
</script>

<style scoped>

</style>
