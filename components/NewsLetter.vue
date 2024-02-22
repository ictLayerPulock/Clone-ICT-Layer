<template>
  <div class="flex pt-5">
    <div class="bg-gray-200 h-8 w-[20%]"></div>
    <div class="bg-orange-300 h-8 w-[81px]"></div>
    <div class="bg-gray-200 h-8 w-[1059px]"></div>
  </div>
  <div class="flex">
    <div class="bg-gray-200 h-20 w-[20%]"></div>
    <div class="bg-gray-500 h-20 w-[60%] flex">
      <div class="h-20 p-4 bg-orange-600">
        <img
          class="p-3 mx-auto rounded-full ring-2 ring-neutral-50 sm:mx-0 sm:flex-shrink-0 transform hover:scale-105 duration-500"
          src="../assets/img/news-letter/mail.svg"
          alt=""
        />
      </div>

      <div class="flex">
        <div>
          <p class="pt-6 pl-16 text-3xl text-gray-50">NEWSLETTER</p>
        </div>
        <div class="flex justify-between pl-[510px]">
          <p class="">
            <input
              class="h-16 text-center pt-5 outline-none"
              type="text"
              placeholder="YOUR EMAIL HERE"
            />
          </p>
          <div>
            <a href="">
              <div
                class="text-center pt-6 text-xl box-border h-20 w-32 p-4 text-white bg-orange-600 hover:text-white hover:bg-gray-700 hover:border-transparent focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-offset-2"
              >
                SIGN UP
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-gray-500 h-20 w-[20%]"></div>
  </div>
</template>