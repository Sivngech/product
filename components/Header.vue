<template>

    <header>


        <div class="company-name">
            Company-Name
        </div>
        <nav>
            <ul>
                <li v-for="item in menuItems" :key="item.path">
                    <NuxtLink :to="item.path" class="menu" exact-active-class="nav-active">
                        {{ item.name }}
                    </NuxtLink>
                </li>
            
            </ul>
        </nav>

        <div class="grid grid-cols-3 w-70">
            <input type="search" placeholder="Search">
            <div class="flex w-100">
                <a href="/cart.vue"><img src="public/images/Shopcart.png" alt=""><h1>Cart(0)</h1></a>
            </div>
            <div>
                <img src="public/images/User.png" alt="">

            </div>
            
        </div>
    </header>
</template>

<script setup>
const menuItems = [
    { name: 'Home', path: '/home' },
    { name: 'Shop', path: '/shop' },
    { name: 'Offers', path: '/offer' },
    { name: 'Our story', path: '/ourstory' },
    { name: 'Blog', path: '/blog' }
]
</script>