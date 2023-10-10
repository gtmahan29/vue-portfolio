<template>
    <div class="service-card">
        <div class="card bg-lightGray hover:shadow-xl hover:bg-[#0252CD] hover:transition hover:duration-200">
            <div class="card-body group test items-start">
                <div class="py-4 px-6 bg-[#0252CD] text-white text-2xl rounded-xl group-hover:bg-white group-hover:text-[#0252CD] group-hover:transition group-hover:duration-200">
                    <font-awesome-icon :icon=props.icon />
                </div>
                <div class="card-content mt-32 flex flex-col gap-6 group-hover:text-white">
                    <h2 class="text-3xl font-bold">{{ title }}</h2>
                    <p>{{ desc }}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps(['title', 'desc', 'icon'])
</script>

<style lang="scss" scoped>

</style>