<template>
    <div class="navbar container mx-auto px-12 bg-lightGray py-5">
        <div class="navbar-start">
            <div class="dropdown">
                <div class="w-12">
                    <router-link to="/">
                        <img src="../assets/Logo.png" alt="">
                    </router-link>
                </div>
            </div>
        </div>
        <div class="navbar-center hidden lg:flex">
            <ul class="menu menu-horizontal px-1 text-gray font-bold tracking-tighter">
                <li class="hover:text-black">
                    <router-link to="/" class="hover:bg-transparent">
                        Home
                    </router-link>
                </li>
                <li class="hover:text-black bg-transparent">
                    <router-link to="/services" class="hover:bg-transparent">
                        Services
                    </router-link>
                </li>
                <li class="hover:text-black bg-transparent">
                    <router-link to="/about" class="hover:bg-transparent">
                        About Me
                    </router-link>
                </li>
                <li class="hover:text-black bg-transparent">
                    <router-link to="/contacts" class="hover:bg-transparent">
                        Contact Me
                    </router-link>
                </li>
            </ul>
        </div>
        <div class="navbar-end">
            <button class="btn btn-outline border-gray rounded-full text-xs px-8">
                Get in touch
            </button>
        </div>
    </div>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>