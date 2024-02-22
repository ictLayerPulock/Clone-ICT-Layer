<template>
  <div class="grid grid-cols-5 h-10">
    <div class="bg-gray-200"></div>
    <div class="col-span-3">
      <div class="grid grid-cols-7">
        <div class="bg-orange-600">
          <div class="grid grid-cols-2">
            <div class="bg-[#ffab90] h-10"></div>
            <div class="bg-gray-200"></div>
          </div>
        </div>
        <div class="bg-gray-200 col-span-6"></div>
      </div>
    </div>
    <div class=""></div>
  </div>

  <div class="grid grid-cols-5">
    <div class="bg-gray-200"></div>
    <div class="col-span-3">
      <div class="grid grid-cols-7">
        <div class="bg-orange-600">
          <div class="grid grid-cols-2">
            <div class="p-4 pt-4 bg-orange-600">
              <img
                class="p-3 mx-auto rounded-full ring-2 ring-neutral-50 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
                src="../assets/img/news-letter/mail.svg"
                alt=""
              />
            </div>
            <div class="bg-gray-500"></div>
          </div>
        </div>
        <div class="bg-gray-500 col-span-4">
          <p class="text-3xl pt-5 text-gray-50">NEWSLETTER</p>
        </div>
        <div class="bg-gray-500">
            <p class="pb-5">
            <input
              class=" text-center py-4 outline-none"
              type="text"
              placeholder="YOUR EMAIL HERE"
            />
          </p>
        </div>
        <div class="bg-orange-600">
            <p class="text-xl box-border text-center py-6 text-white bg-orange-600 hover:text-white hover:bg-gray-700 hover:border-transparent focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-offset-2">SIGN UP</p>
        </div>
      </div>
    </div>
    <div class="bg-gray-500"></div>
  </div>
</template>