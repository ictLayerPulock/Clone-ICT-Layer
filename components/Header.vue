<template>
  <header
    class="sticky  top-0 container flex flex-cjol sm:flex-row items-center gap-4 text-white pt-5 mx-auto"
  >
    <nav class="">
      <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8"> 
        
        <div class="relative flex h-16 items-center justify-between">
          <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
            <!-- Mobile menu button-->
          </div>
          <div
            class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start"
          >
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

            <div class="hidden sm:block pl-64">
              <div class="flex space-x-1">
                <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->

                <NuxtLink
                  to="/"
                  class="bg-orange-600 text-gray-400 p-10 text-sm font-medium"
                >
                  <img
                    class=" p-2 mx-auto rounded-full ring-2 ring-neutral-50 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                    src="../assets/img/icon_house_alt.svg"
                    alt=""
                  />
                  <p class="pt-4 text-neutral-50">HOME</p>
                </NuxtLink>
                <NuxtLink
                  to="/"
                  class="bg-gray-100 text-gray-400 p-10 text-sm font-medium mx-0 hover:bg-orange-600 "
                >
                  <img
                    class="p-2 mx-auto rounded-full ring-2 ring-gray-400 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                    src="../assets/img/service.svg"
                    alt=""
                  />
                  <p class="pt-4 text-gray-400">ICT Service</p>
                </NuxtLink>

                <NuxtLink
                  to="/"
                  class="bg-gray-100 text-gray-400 p-10 text-sm font-medium hover:bg-orange-600 "
                >
                  <img
                    class="p-2 mx-auto rounded-full ring-2 ring-gray-400 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                    src="../assets/img/toolbox.svg"
                    alt=""
                  />
                  <p class="pt-4">PROTFOLIO</p>
                </NuxtLink>

                <NuxtLink
                  to="/"
                  class="bg-gray-100 text-gray-400 p-7 pt-12 text-sm font-medium hover:bg-orange-600 "
                >
                  <img
                    class="p-2 mx-auto rounded-full ring-2 ring-gray-400 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                    src="../assets/img/icon_pens.svg"
                    alt=""
                  />
                  <p class="pt-4">PACKAGES</p>
                </NuxtLink>

                <NuxtLink
                  to="/"
                  class="bg-gray-100 text-gray-400 p-7 pt-12 text-sm font-medium hover:bg-orange-600 "
                >
                  <img
                    class="p-2 mx-auto rounded-full ring-2 ring-gray-400 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                    src="../assets/img/mail.svg"
                    alt=""
                  />
                  <p class="pt-4">CONTACT</p>
                </NuxtLink>

                <NuxtLink
                  to="/"
                  class="bg-gray-100 text-gray-400 p-9 pt-12 text-sm font-medium hover:bg-orange-600 "
                >
                  <img
                    class="p-2 mx-auto rounded-full ring-2 ring-gray-400 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                    src="../assets/img/search.svg"
                    alt=""
                  />
                </NuxtLink>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Mobile menu, show/hide based on menu state. -->
      <!-- <div class="sm:hidden" id="mobile-menu">
        <div class="space-y-1 px-2 pb-3 pt-2">
          <a
            to="/"
            class="bg-gray-900 text-white block rounded-md px-3 py-2 text-base font-medium"
            aria-current="page"
            >Dashboard</a
          >
          <a
            to="/"
            class="text-gray-300 bg-gray-700 hover:text-white block rounded-md px-3 py-2 text-base font-medium"
            >Team</a
          >
          <a
            to="/"
            class="text-gray-300 hover:bg-gray-700 hover:text-white block rounded-md px-3 py-2 text-base font-medium"
            >Projects</a
          >
          <a
            to="/"
            class="text-gray-300 hover:bg-gray-700 hover:text-white block rounded-md px-3 py-2 text-base font-medium"
            >Calendar</a
          >
        </div>
      </div> -->
    </nav>
  </header>

  <!-- <div class="columns-12">
    <div class="columns-6">
        <div>
            <NuxtLink
              to="/"
              class="bg-gray-100 text-white p-6 pt-12 text-sm font-medium"
            >
              <img
                class="p-2 mx-auto ring-gray-400 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                src="../assets/img/logo.png"
                alt=""
              />
            </NuxtLink>
        </div>
    </div>
    <div class="columns-6"></div>
  </div> -->
</template>