<template>
    <div class="project flex flex-col p-8 text-white rounded-xl" :class="props.color">
        <div class="project-title">
            <div class="flex flex-col gap-2 items-start">
                <h2 class="text-3xl font-bold">{{ props.title }}</h2>
                <span class="project-tag p-2 mt-2 rounded-md text-sm text-white bg-white bg-opacity-20">{{ props.tags }}</span>
            </div>
        </div>
        <div class="project-img">
            <img :src=props.image alt="" class="w-full">
        </div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps(['title', 'tags', 'color', 'image'])
</script>

<style lang="scss" scoped>

</style>