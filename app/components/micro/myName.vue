<script>
import Github from './github.vue';
import Instagram from './instagram.vue';
import Linkedin from './linkedin.vue';

export default {
    components: {
        Github,
        Linkedin,
        Instagram
    }
}
</script>
<template>
    <div class="justify-self-center sm:text-left">
        <div class="mt-20 mb-9">
            <h1 class="text-2xl mb-2">Olá meu nome é Andersson</h1>
            <p>Sou desenvolvedor Front-end</p>
        </div>

        <div class="gap-10 hidden sm:flex">
            <Github/>
            <Linkedin/>
            <Instagram/>
        </div>
    </div>
</template>