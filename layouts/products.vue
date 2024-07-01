<template>
    <div>
        <header class=" shadow-sm bg-white">
            <nav class="container mx-auto py-4 flex justify-between">
                <NuxtLink
                    to="/products"
                    class="font-bold"
                >Nuxt Dojo Merch</NuxtLink>
            </nav>
        </header>
        <div>
            <slot />
        </div>
        <footer class="  border-t-2">
            <ul class=" container mx-auto flex gap-4 py-4">
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/products" >Products</NuxtLink></li>
            </ul>
        </footer>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: #12b488;
}
</style>