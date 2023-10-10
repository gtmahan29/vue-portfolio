<template>
    <div class="hero container mx-auto px-12 bg-lightGray flex h-full items-start justify-between">
        <div class="hero-content flex flex-col gap-6 justify-center items-start mt-12 w-6/12">
            <span class="text-primary tracking-widest3x text-xs font-bold">HI, I AM MAHAN</span>
            <div class="hero-title flex flex-col">
                <span class="text-[66px] font-bold">
                    Proffesional 
                </span>
                <span class="text-[66px] font-bold">
                    Front-End
                </span>
                <span class="text-[66px] font-bold z-10">
                    Web Developer
                </span>
            </div>
            <p class="w-5/6">Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed. Ullamcorper tellus ac cras nec, pretium laoreet duis. </p>
            <div class="btn-actions flex items-center gap-8">
                <button class="btn bg-primary rounded-full text-white text-xs capitalize px-8 hover:bg-blue-500">Contact Me</button>
                <div class="social-links flex gap-8">
                    <a href="#" class="text-3xl text-gray hover:text-black transition duration-300">
                        <font-awesome-icon icon="fa-brands fa-instagram" />
                    </a>
                    <a href="#" class="text-3xl text-gray hover:text-black transition duration-300">
                        <font-awesome-icon icon="fa-brands fa-telegram" />
                    </a>
                    <a href="#" class="text-3xl text-gray hover:text-black transition duration-300">
                        <font-awesome-icon icon="fa-brands fa-linkedin" />
                    </a>
                </div>
            </div>
        </div>
        <div class="hero-image w-6/12 h-full mx-auto">
            <img src="@/src/assets/Hero-background.png" alt="" class="h-full">
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