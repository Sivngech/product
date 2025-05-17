<template>
   <section class="section1" style="background-image: url('/images/download 1.png');">

      <div class="left-script">
         <h1>Gift for your skin</h1>
         <p>Aliquip fugiat ipsum nostrud ex et eu incididunt quis minim dolore excepteur voluptate</p>

      </div>
   </section>

   <section class="section2">
      <div style=" font-size: 24px;">Our Product<button class="border text-green-300 text-right">See all</button></div>

      <div class="con-button">

         <button class="best-seller" @click="active = 'best'">Best-seller</button>
         <button class="new-product" @click="active = 'new'">New Products</button>


         <div v-if="active === 'best'">
            <h2>best seller products</h2>

         </div>

         <div v-else-if="active === 'new'">
            <h2>new products</h2>
         </div>
      </div>


      <div class="grid grid-cols-4 gap-4">

         <div class="w-60 shadow">
            <img src="public/images/producImage.png" alt="image">
            <h5 class="text-center">Product Title</h5>
            <h6>Deserunt non fugiat aute cons</h6>
            <div class="flex gap-3 p-5">
               <span>$32</span>
               <span><s>$42</s></span>
               <span><button> <img src="public/images/Button.png" alt="image"></button></span>
            </div>
         </div>
         <div class="w-60 shadow">
            <img src="public/images/image2.png" alt="image">
            <h5 class="text-center">Product Title</h5>
            <h6>Ut nostrud esse aute ipsum vo</h6>
            <div class="flex gap-3 p-5">
               <span>$22</span>
               <span><s>$28</s></span>
               <span><button> <img src="public/images/Button.png" alt="image"></button></span>
            </div>
         </div>
         <div class="w-60 shadow">
            <img src="public/images/image3.png" alt="image">
            <h5 class="text-center">Product Title</h5>
            <h6>Culpa ea exercitation amet co</h6>
            <div class="flex gap-3 p-5">
               <span>$18</span>
               <span><s>$26</s></span>
               <span><button> <img src="public/images/Button.png" alt="image"></button></span>
            </div>
         </div>
         <div class="w-60 shadow">
            <img src="public/images/image4.png" alt="image">
            <h5 class="text-center">Product Title</h5>
            <h6>Est veniam anim aute exercita</h6>
            <div class="flex gap-3 p-5">
               <span>$48</span>
               <span><s>$56</s></span>
               <span><button> <img src="public/images/Button.png" alt="image"></button></span>
            </div>
         </div>
      </div>
   </section>


   <section class="h-100">
      <h1 class="text-center">Event Promotion</h1>
      <div class="flex w-full-[400px]">
         <div class="flex-1 bg-no-repeat bg-cover bg-left" style="background-image: url('/images/Image-bg1.png');">
            <div>
               <h1>Relaxing & <br> Pampering</h1>
               <p>Pariatur ad nisi ex tempor ea</p>
               <button class="bg-sky-300">Explore</button>
            </div>
         </div>
         <div class="w-[563px] h-[338px] bg-no-repeat bg-cover bg-right m-1"
            style="background-image: url('/images/Image-bg2.png');">
            <div>
               <h1>Relaxing & <br> Pampering</h1>
               <p>Pariatur ad nisi ex tempor ea</p>
               <button class="bg-sky-300">Explore</button>
            </div>
         </div>

      </div>
   </section>


   <section class="h-170">
      <div>Our Story
         <button class="border text-green-300 text-right">See all</button>
      </div>

      <div class="h-150" style="background-image: url('/images/videoImg.png');">
         <button class="border-none bg-black text-white rounded">Watch video <img src="public/images/playIcon.png"
               alt=""></button>
      </div>
   </section>


   <section class="h-100">
      <div class="grid grid-cols-3">
         <div class="w-90">
            <h1>Read What’s New</h1>
            <p>Sint consequat in ipsum irure adipisicing dolore culpa incididunt. Veniam elit magna anim ipsum eiusmod
               eu</p>
            <div class="grid grid-cols-3">
               <button class="border text-green-500 rounded p-4">Explore more</button>
               <button><img src="public/images/Button 1.png" alt="image"></button>
               <button><img src="public/images/Button 2.png" alt="image"></button>
            </div>

         </div>

         <div class="w-90 shadow rounded p-3.5">
            <img src="public/images/card1.png" alt="">
            <p>Anim sint Lorem excepteur <br> commodo </p>
            <p>Oct 12, 2022</p>
         </div>

         <div class="w-90 shadow rounded p-3.5">
            <img src="public/images/Image.png" alt="image">
            <p>Adipisicing elit proident in elit  <br> magna deser </p>
            <p>Oct 12, 2022</p>
         </div>
      </div>
   </section>

   <section class="h-150">
      <div class="text-center">
         <h1 class="font-bold text-4x1">Instagram</h1>
         <p>@yourinstagram_offical</p>
      </div>
      <div class="grid grid-cols-6">
         <img src="public/images/Image 36.png" alt="image">
         <img src="public/images/Image 34.png" alt="">
         <img src="public/images/Image 35.png" alt="">
         <img src="public/images/Image 32.png" alt="">
         <img src="public/images/Image 31.png" alt="">
         <img src="public/images/Image 37.png" alt="">
      </div>

      <div class="grid grid-cols-6">
         <img src="public/images/Image 36.png" alt="image">
         <img src="public/images/Image 34.png" alt="">
         <img src="public/images/Image 35.png" alt="">
         <img src="public/images/Image 32.png" alt="">
         <img src="public/images/Image 31.png" alt="">
         <img src="public/images/Image 37.png" alt="">
      </div>
   </section>



</template>
<script setup>
import { ref } from 'vue'

const active = ref('best')
</script>
