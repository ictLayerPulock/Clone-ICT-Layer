<template>
  <div class="sticky  top-0">
    <div class="w-full h-32 border-b[1px] border-gray-500 text-black">
      <div
        class="max-w-screen-2xl mx-auto px-4 flex items-center justify-between"
      >
        <h1>
          <NuxtLink
            to="/"
            class="bg-gray-100 text-white p-6 ml- pt-20 text-sm font-medium"
          >
            <img
              class="p-2 mx-auto ring-gray-400 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
              src="../assets/img/logo.png"
              alt=""
            />
          </NuxtLink>
        </h1>
        <ul class="flex items-center gap-8 uppercase">
          <li class="navbaLi"></li>
          <li class="navbaLi">About</li>
          <li class="navbaLi">Contact</li>
          <li class="navbaLi">Service</li>
        </ul>
        <div></div>
      </div>
    </div>
  </div>
</template>