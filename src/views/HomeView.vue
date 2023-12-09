<template>
  <div class="flex flex-col px-6 container mx-auto py-3">
    <div class="flex flex-wrap">
      <div class="grid grid-cols-2 lg:w-1/2 w-96 bg-orange-600">
        <div class="py-1 pl-2">WHAT'S ON TONIGHT</div>
        <div class="bg-yellow-600 text-end py-1 pr-2">00.00 P.PM.(E/P)</div>
      </div>

      <div class="bg-yellow-500 px-3 py-1">TV SCHEDULE</div>
      <div class="flex flex-end gap-4 bg-gray-500 pl-12 pr-3 py-1">
        <div>HELP</div>
        <div>SITEMAP</div>
      </div>
      <div class="flex bg-gray-300 px-3 py-1">
        <div>SEARCH</div>
        <input type="text" class="border outline-none" />
        <div>GO</div>
      </div>
    </div>
    <div class="flex flex-col md:flex-row flex-grow gap-8 mt-8">
      <div class="flex flex-col bg-black">
        <div class="h-96 w-48">a</div>
      </div>
      <div class="flex flex-col gap-4 w-full">
        <div class="w-full grid grid-cols-3">
          <div class="col-span-2 border">content</div>
          <div class="border">content</div>
        </div>
        <div class="w-full grid grid-cols-3">
          <div class="border">content</div>
          <div class="border">content</div>
          <div class="border">content</div>
        </div>
        <div class="w-full grid grid-cols-3">
          <div class="border">content</div>
          <div class="border">content</div>
          <div class="border">content</div>
        </div>
        <div>PRIVACY POLICY</div>
        <div class="flex gap-2 flex-wrap">

          <div>TRADEMARK INFORMATION</div>
          <div>TERMS OF USE</div>
          <div>PARENT GUIDE</div>
          <div>TV PARENTAL GUIDELINES</div>
        </div>
        <div>USE OF THIS SITE SIGNIFIES TOUR AGREEMENT TO THE TERMS OF USE</div>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts"></script>
