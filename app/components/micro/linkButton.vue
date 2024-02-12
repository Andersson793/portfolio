<script>
export default {
    props:{
        href:String
    }
}
</script>
<template>
        <div style="background-color: rgba(126, 182, 255, 0.2);" class="rounded-md py-2 px-3 text-sm max-w-fit mx-auto flex items-center">
            <a :href=href class="inline-flex items-center">
                <img src="/link.svg" alt="to" class="h-5 mr-4">
                <p style="color: #87c5ff;">{{ href }}</p>
            </a>
        </div>
</template>