<template>
  <form class="bg-green-500 rounded mx-auto px-6 py-6 w-1/2">
    <div class="flex flex-col">
      <label for="name" class="text-white text-xl">Name</label>
      <input type="text" class="px-2 py-1 rounded" placeholder="Name">
      <span class="text-red-200 italic"></span>
    </div>
    <div class="flex flex-col mt-3">
      <label for="username" class="text-white text-xl">Username</label>
      <input type="text" class="px-2 py-1 rounded" placeholder="Username">
      <span class="text-red-200 italic"></span>
    </div>
    <div class="flex flex-col mt-3">
      <label for="email" class="text-white text-xl">Email</label>
      <input type="email" class="px-2 py-1 rounded" placeholder="Email">
      <span class="text-red-200 italic"></span>

    </div>
    <div class="flex flex-col mt-3">
      <label for="password" class="text-white text-xl">Password</label>
      <input type="password" class="px-2 py-1 rounded" placeholder="Password">
      <span class="text-red-200 italic"></span>

    </div>
    <div class="flex flex-col mt-3">
      <label for="password_confirmation" class="text-white text-xl">Confirm Password</label>
      <input type="password" class="px-2 py-1 rounded"
             placeholder="Confirm Password">
    </div>
    <div class="flex items-baseline justify-between mt-3">
      <button type="button"
              class="inline-flex items-center justify-center px-4 py-2 bg-teal-300 border border-transparent rounded-md font-semibold text-teal-700 uppercase tracking-widest hover:bg-green-700 hover:text-gray-200 focus:outline-none focus:border-blue-700 focus:shadow-outline-blue active:bg-teal-300 transition ease-in-out duration-150">
        Register
      </button>
      <div>
        Already have an account?
        <NuxtLink to="/auth/login" class="text-sm text-white hover:underline hover:text-green-200">
          LOGIN
        </NuxtLink>
      </div>
    </div>
  </form>
</template>

<script>
export default {
  name: "register",
  layout: 'guest'
}
</script>

<style scoped>

</style>
