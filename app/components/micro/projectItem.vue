<script>
import linkButton from '../micro/linkButton.vue'
export default {
    props: {
        link: String,
        href: String,
        asset: String
    },
    components: { 
        linkButton
    }
}
</script>
<template>
    <div class="text-center max-w-80 flex-col col-span-full sm:col-span-1">

        <img :src=asset class="h-8 w-full mb-9" alt="image">

        <p class="mb-9">
            <slot></slot>
        </p>
        
        <linkButton :href=href />

    </div>
</template>