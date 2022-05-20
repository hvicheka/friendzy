<template>
  <div>
    <div class="bg-green-500 text-white text-md">
      <nav class="container flex justify-between items-center max-w-6xl mx-auto py-5 sm:px-6 lg:px-8">
        <span class="font-semibold text-2xl">Friendzy</span>
        <div class="space-x-2">
          <template>
            <span>Welcome,
              <NuxtLink to="#" class="capitalize hover:text-green-200">
                Vicheka
              </NuxtLink>
            </span>
            <NuxtLink to="#" class="hover:text-green-200">
              FRIENDS
            </NuxtLink>
            <NuxtLink to="#" class="hover:text-green-200">
              USERS
            </NuxtLink>
            <NuxtLink to="/dashboard" class="hover:text-green-200">
              DASHBOARD
            </NuxtLink>
            <NuxtLink to="#" class="hover:text-green-200">
              REGISTER
            </NuxtLink>
            <NuxtLink to="#" class="hover:text-green-200">
              LOGIN
            </NuxtLink>
          </template>
        </div>
      </nav>
    </div>
    <Nuxt/>
  </div>
</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>

</style>
