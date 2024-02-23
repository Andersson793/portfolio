<script>
import Section from './micro/section.vue';
import SubTitles from './micro/subTitles.vue';

export default {
    components:{
    SubTitles,
    Section
}
}
</script>
<template>
    <footer id="contato" class="mb-12 text-center">
        <h4 class="mb-16">Gostaria de entrar em contato ?</h4>

        <div class="grid grid-cols-3 justify-items-center sm:gap-x-32 gap-x-16 max-w-fit mx-auto">

            <a href="https://www.linkedin.com/in/andersson-silva-gon%C3%A7alves-2a6839203/">
                <img src="/linkedin.svg" alt="Linkedin" class="w-7">
            </a>

            <a href="mailto:anderssonsilva793@gmail.com">
                <img src="/email.svg" alt="E-mail" class="w-7">
            </a>

            <a href="https://t.me/anderssongoncalves">
                <img src="/telegram.svg" alt="Telegram" class="w-7">
            </a>
        </div>
    </footer>
</template>