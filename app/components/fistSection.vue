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
    <section class="grid grid-cols-2 h-96 mt-28">
        <MyName/>
        <Circle/>
    </section>
</template>