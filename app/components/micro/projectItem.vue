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
    <div class="text-center max-w-80 flex-col">

        <img :src=asset class="h-9 w-full mb-9" alt="image">

        <p class="mb-9">
            <slot></slot>
        </p>
        
        <linkButton :href=href />

    </div>
</template>