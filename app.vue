<template>

  <div class="bg-[#1C233A] min-h-screen flex flex-col ">
    <div class="container mx-auto min-h-screen flex flex-col">
      <img src="~~/assets/img/nav.png" class="my-9" alt="">
      <div class="flex justify-items-start items-center">
        <div class="min-w-[300px] w-4/6 flex flex-col">
          <img class="mr-4" src="~~/assets/img/Video.png" alt="">
          <div class=" min-w-[300px] w-5/6 ">
            <TitleCustom/>
          </div>
          <div class=" min-w-[300px] w-5/6 ">
            <AdditionalContent/>
          </div>
        </div>
        <div class="self-start w-4/12">
          <comment/>
          <div class="p-2 flex flex-col">
            <div class="py-5">
              <ShowComment/>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>


import ShowComment from "./components/ShowCommet/ShowComment";
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700;900&display=swap');

    body{
        font-family: 'Montserrat', sans-serif;
    }
</style>
