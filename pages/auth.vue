<script setup>
  const email = '',
  password = '';
</script>

<template>
  
  <div class="flex h-screen w-full items-center justify-center bg-cover bg-no-repeat wrapper">
    <div class="rounded-xl w-2/4 bg-green-800 bg-opacity-50 px-16 shadow-lg backdrop-blur-md max-sm:px-8">
      <div class="text-white py-10">
        <div class="mb-8 flex flex-col items-center">
          <h1 class="mb-2 text-2xl">Le vin en rose</h1>
        </div>
        <div class="mb-4 text-lg flex justify-center">
          <input class="rounded-3xl border-none w-1/2 bg-green-400 bg-opacity-50 px-6 py-2 text-center text-inherit placeholder-slate-200 shadow-lg outline-none backdrop-blur-md" type="text" name="name" placeholder="id@email.com" v-model="email" />
        </div>

        <div class="mb-4 text-lg flex justify-center">
          <input class="rounded-3xl border-none w-1/2 bg-green-400 bg-opacity-50 px-6 py-2 text-center text-inherit placeholder-slate-200 shadow-lg outline-none backdrop-blur-md" type="Password" name="name" placeholder="*********" v-model="password"/>
        </div>
        <div class="mt-20 flex justify-around text-lg text-black">
          <button type="submit" class="rounded-3xl min-w-1/2 bg-green-400 bg-opacity-50 px-10 py-2 text-white shadow-xl backdrop-blur-md transition-colors duration-300 hover:bg-yellow-600">Se connecter</button>
        </div>
      </div>
      <div class="flex justify-center">
        <NuxtLink to="/signup" class="bottom-0 text-white">Créer un compte</NuxtLink>
      </div>
    </div>
  </div>

</template>

<style>

</style>