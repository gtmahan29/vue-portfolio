<template>
    <div class="work-experience flex justify-between gap-8">
        <div class="experience-about py-36 px-28 bg-darkBlue text-white basis-1/2 rounded-2xl text-start bg-cover bg-[center_top_5rem] bg-no-repeat">
            <h2 class="text-[40px] font-bold mb-8">Working <br/> Experience</h2>
            <p class="mb-16">Tincidunt purus lacus nascetur nunc commodo. Netus at dignissim urna quam. Imperdiet proin sapien posuere egestas. Tristique nam magna velit odio ullamcorper eget donec.</p>
        </div>
        <div class="experience-status basis-1/2 flex flex-col justify-between">
            <div v-for="item in experiences" :key="item.index" class="experience-details rounded-2xl flex items-center gap-8 border border-[#e7e7e7] p-8 duration-200 hover:border-transparent hover:translate-x-4 hover:duration-200">
                <div class="company-logo text-6xl">
                    <font-awesome-icon :icon=item.icon />
                </div>
                <div class="experience-desc h-full flex flex-col gap-2 justify-center">
                    <h4 class="font-bold text-xl">{{ item.company }}</h4>
                    <span class="text-xs text-gray">{{ item.position }} <span>{{ item.time }}</span></span>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { reactive } from "vue";

const experiences = reactive([
    {
        index: 1,
        company: 'Slack',
        position: 'Front-End Developer',
        time: '1 Year Experience',
        icon: 'fa-brands fa-instagram',
    },
    {
        index: 2,
        company: 'Slack',
        position: 'Front-End Developer',
        time: '1 Year Experience',
        icon: 'fa-brands fa-instagram',
    },
    {
        index: 3,
        company: 'Slack',
        position: 'Front-End Developer',
        time: '1 Year Experience',
        icon: 'fa-brands fa-instagram',
    },
    {
        index: 4,
        company: 'Slack',
        position: 'Front-End Developer',
        time: '1 Year Experience',
        icon: 'fa-brands fa-instagram',
    },
])
</script>

<style lang="scss" scoped>

</style>