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
            <h1 class="text-4xl mb-2">Olá meu nome é Andersson</h1>
            <p class="text-lg sub-text">Sou desenvolvedor Front end</p>
        </div>

        <div class="flex gap-10">
            <Github/>
            <Linkedin/>
            <Instagram/>
        </div>
    </div>
</template>