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
    <div class="justify-self-center">
        <div class="mt-20 mb-9">
            <h1 class="text-2xl mb-2">Olá meu nome é Andersson</h1>
            <p class="text-md sub-text">Sou desenvolvedor Front-end</p>
        </div>

        <div class="flex:md gap-10 hidden">
            <Github/>
            <Linkedin/>
            <Instagram/>
        </div>
    </div>
</template>