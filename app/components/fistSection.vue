<script>
import Circle from './micro/circle.vue';
import MyName from './micro/myName.vue';

export default {
    components : {
        Circle,
        MyName
    }
}
</script>
<template>
    <section class="grid grid-cols-2 h-96 mt-28 text-center">
        <MyName class="col-span-full sm:col-span-1"/>
        <Circle class="order-first sm:order-last col-span-full sm:col-span-1"/>
    </section>
</template>