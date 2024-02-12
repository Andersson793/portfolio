<script>
export default {
    props : {
        title:String,
        asset:String
    }
}
</script>
<template>
    <div class="flex text-left">

        <div>
            <p class="mb-4 font-bold">{{ title }}</p>
            <p class="max-w-72">
                <slot></slot>
            </p>
        </div>

        <img :src=asset alt="image" class="h-16 ml-4">

    </div>
</template>