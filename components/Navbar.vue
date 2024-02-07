<template>
  <div class="sticky top-0 z-10">
    <div class="w-full h-32 border-b[1px] border-gray-500 text-black">
      <div
        class="max-w-screen-xl mx-auto px-6 flex items-center justify-between"
      >
        <div class="box-border h-32 w-32 p-4 bg-gray-300">
          <img
            class="absolute bottom-5 pl-6"
            src="../assets/img/navbar/logo.png"
            alt=""
          />
        </div>
        <div>
          <ul class="flex uppercase">
            <li
              class="bg-orange-600 text-gray-400 box-border h-32 w-32 p-4 border-r"
            >
              <div class="flex justify-center py-4">
                <img
                  class="p-2 rounded-full ring-2 ring-gray-100 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                  src="../assets/img/navbar/icon_house_alt.svg"
                  alt=""
                />
              </div>

              <p class="flex justify-end text-white">Home</p>
            </li>
            <li
              class="box-border h-32 w-32 p-5 border-r bg-gray-100 hover:bg-orange-600 hover:text-gray-50 hover:ring-gray-100"
            >
              <div class="flex justify-center py-4">
                <img
                  class="p-2 rounded-full ring-2 ring-gray-400 hover:ring-gray-50 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                  src="../assets/img/navbar/service.svg"
                  alt=""
                />
              </div>

              <p class="flex justify-end">ICT Service</p>
            </li>
            <li
              class="box-border h-32 w-32 p-4 border-r bg-gray-100 hover:bg-orange-600 hover:text-gray-50"
            >
              <div class="flex justify-center py-4">
                <img
                  class="p-2 rounded-full ring-2 ring-gray-400 hover:ring-gray-50 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                  src="../assets/img/navbar/toolbox.svg"
                  alt=""
                />
              </div>

              <p class="flex justify-end">PROTFOLIO</p>
            </li>
            <li
              class="box-border h-32 w-32 p-4 border-r bg-gray-100 hover:bg-orange-600 hover:text-gray-50"
            >
              <div class="flex justify-center py-4">
                <img
                  class="p-2 rounded-full ring-2 ring-gray-400 sm:mx-0 hover:ring-gray-50 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                  src="../assets/img/navbar/icon_pens.svg"
                  alt=""
                />
              </div>

              <p class="flex justify-end">PACKAGES</p>
            </li>
            <li
              class="h-32 w-32 p-4 border-r bg-gray-100 hover:bg-orange-600 hover:text-gray-50"
            >
              <div class="flex justify-center py-4">
                <img
                  class="p-2 rounded-full ring-2 ring-gray-400 sm:mx-0 hover:ring-gray-50 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                  src="../assets/img/navbar/mail.svg"
                  alt=""
                />
              </div>

              <p class="flex justify-end">CONTACT</p>
            </li>
            <li
              class="place-content-center box-border h-32 w-32 p-4 bg-gray-100 hover:bg-orange-600 hover:text-gray-50"
            >
              <div class="grid place-items-center">
                <img
                  class="p-2 rounded-full ring-2 ring-gray-400 sm:mx-0 hover:ring-gray-50 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                  src="../assets/img/navbar/search.svg"
                  alt=""
                />
              </div>
            </li>
          </ul>
        </div>

      
      </div>
    </div>
  </div>
</template>