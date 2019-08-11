<template>
    <div class="w-1/2 md:w-1/3 lg:w-1/4 p-4">
        <h3 class="text-gray-900 sm:text-lg lg:text-xl underline font-semibold">{{ title }}</h3>
        <div class="text-gray-700 text-sm sm:text-base lg:text-lg mt-2 sm:mt-3 lg:mt-3">
            <ul>
                <slot></slot>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: "ToolList",
        props: ['title']
    }
</script>