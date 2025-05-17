<template>
    <div class="grid grid-cols-7 text-green-600">
    <NuxtLink to="/product-detail/home">Home</NuxtLink>
    <img src="public/images/Chevron right large.png" alt="">
    <NuxtLink to="/product-detail/shop">Shop</NuxtLink>
    <img src="public/images/Chevron right large.png" alt="">
    <NuxtLink to="/product-detail/">Product Types</NuxtLink>
    <img src="public/images/Chevron right large.png" alt="">
    <NuxtLink class="text-black" to="/product-detail/detail">Detail</NuxtLink>

    </div>

    <section class="h-150">
        <div class="grid grid-cols-3">
            <div class="flex ">
            <div class="flex-1 space-x-4">
                <img src="public/images/Thumbnail 1.png" alt="">
                <img src="public/images/Thumbnail 2.png" alt="">
                <img src="public/images/Thumbnail 3.png" alt="">
                <img src="public/images/Thumbnail 4.png" alt="">
            </div>

            <div class="flex-1">
                <img src="public/images/Serum.png" alt="">
            </div>
        </div>


        <!--<div class="flex-1">
            <h1>Product Name</h1>
            <p>Aliquip fugiat ipsum nostrud ex et eu incididunt</p>

            <div class="flex gap-2" style="font-size:24px;">
            <p class="font-bold text-green-500">$32</p>
            <p>$42</p>
            </div>

            <p>In ullamco labore mollit et exercitation fugiat exercitation minim ex sint ullamco exercitation amet officia mollit. Qui cillum pariatur in con</p>
            <p class="font-bold">368 </p><p>reviews</p>
            
        </div>
        -->


        
  <div class="flex-1 max-w-sm p-4 shadow-sm">
    <h2 class="text-lg font-semibold">Product Name</h2>
    <p class="text-sm text-gray-600">Aliquip fugiat ipsum nostrud ex et eu incididunt</p>

    <div class="flex items-center space-x-2 mt-2">
      <span class="text-2xl font-bold text-green-600">$32</span>
      <span class="line-through text-gray-400">$42</span>
    </div>

    <p class="text-sm text-gray-700 mt-2">
      In ullamco labore mollit et exercitation fugiat exercitation minim ex sint ullamco exercitation amet officia mollit. Qui cillum pariatur in con
    </p>

    <div class="flex items-center mt-4 space-x-4 text-sm text-gray-700 gap-2">
      <span class="font-semibold">368</span><span class="text-gray-500">reviews</span>
      <span class="font-semibold">823</span><span class="text-gray-500">sold</span>
      <div class="flex items-center space-x-1">
        <div class="text-yellow-400">⭐⭐⭐⭐⭐</div>
        <span class="text-gray-800 font-semibold ml-1">4.5</span>
      </div>
    </div>

     <form action="">
    <div class="items-center space-x-2">
    <input class="rounded-full border-gray-300 text-blue-600 focus:ring-blue-500" type="checkbox" id="interest1" >
    <label  for="interest1">Free shipping on orders over $49USD</label>
    </div>

    <div>
    <input class="rounded-full" type="checkbox" id="interest2">
    <label for="interest2">Free + easy returns</label>
    </div>
    
  </form>




  <div>
    choose size
  </div>

    <UButtonGroup>
    <UButton color="neutral" variant="subtle" label="Button" />
    <UButton color="neutral" variant="outline" icon="i-lucide-chevron-down" />
  </UButtonGroup>
  </div>
  


        </div>
        
        

    </section>


    <section>
        <h1>Related Products</h1>


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

    <section>
        <div> 
            <nav>
                <ul>
                    <li class="border green-100 text-green-800 bg-green-100 rounded"><button>Benefits</button></li>
                    <li class="text-green-800"><button>Ingredients</button></li>
                    <li class="text-green-800"><button>How to use</button></li>
                    <li class="text-green-800"><button>Reviews</button></li>
                    <li class="text-green-800"><button>FAQs</button></li>
                </ul>
            </nav>
        </div>
    </section>

    <section class="h-180">
        <div class="flex">
            <div class="flex-1">
                <h1>Benefits</h1>
                <p>Consectetur excepteur elit ullamco incididunt voluptate tempor exercitation. Lorem commodo ullamco quis velit officia aute laboris elit sit exercitation ut esse pariatur occaecat quis</p>
                <h1>Laboris consequat ad </h1>
                <p>Consectetur excepteur elit ullamco incididunt voluptate tempor exercitation. Lorem commodo ullamco quis velit officia aute laboris elit sit exercitation ut esse pariatur</p>
                <h1>Duis duis do labore pariatur </h1>
                <p>Ad qui aliqua nulla nostrud consectetur laboris nostrud commodo voluptate. Lorem id qui laborum aute voluptate </p>
                <h1>Deserunt ex </h1>
                <p>Cupidatat culpa id do laboris nisi aliqua eu. Veniam aliqua duis Lorem adipisicing et minim velit quis </p>
            
            
            </div>
            <div class="flex-1">
                <img src="public/images/pi1.png" alt="">
            </div>
        </div>

    </section>
    





</template>
<script setup lang="ts">
    // const value = ref(true)


</script>