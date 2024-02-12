<script>
import ProjectItem from './micro/projectItem.vue';
import Section from './micro/section.vue';
import SubTitles from './micro/subTitles.vue';

export default {
    components :{
    SubTitles,
    ProjectItem,
    Section
}
}
</script>
<template>
    <Section>

        <SubTitles>
            projetos
        </SubTitles>

        <div class="grid grid-cols-3 col-span-6 gap-x-9 justify-items-center">
            <ProjectItem asset="/nosso fut logo.svg" href="https://www.nossofut.com/">
                Um site de futebol que desenvolvi, que consome os dados de uma API em tempo real.
            </ProjectItem>

            <ProjectItem asset="/fume artes logo.svg" href="https://www.nossofut.com/">
                Site para um cliente de uma loja de fumê automotivo.
            </ProjectItem>

            <ProjectItem asset="/meu cep logo.svg" href="https://www.nossofut.com/">
                Site para pesquisa de CEP, desenvolvi utilizando a API viacep.
            </ProjectItem>
        </div>
    </Section>
</template>