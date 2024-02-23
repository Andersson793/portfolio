<script>
import KnowledgeItem from './micro/knowledgeItem.vue';
import Section from './micro/section.vue';
import SubTitles from './micro/subTitles.vue';

export default {
    components: {
    SubTitles,
    KnowledgeItem,
    Section
}
}
</script>
<template>
    <Section>
        <SubTitles>
            conhecimnetos
        </SubTitles>

        <div class="grid grid-cols-3 auto-rows-auto gap-x-9 gap-y-24 justify-items-center">

            <KnowledgeItem title="Frontend" asset="/front end.svg">
                Conhecimnetos em Front-end que incluem <b>HTML</b>, <b>CSS</b>, e <b>Javascript</b>, <b>Vue.js</b> e <b>React.js</b>.
            </KnowledgeItem>

            <KnowledgeItem title="Backend" asset="/backend.svg">
                Conhecimento em back-end com <b>PHP</b> e <b>Node.js</b>.
            </KnowledgeItem>

            <KnowledgeItem title="Linux" asset="/linux-logo.svg">
                Conhecimneto em linux com <b>Shell Script</b>, <b>gerenciadores de pacotes</b>, e <b>máquinas virtuais</b>.
            </KnowledgeItem>

        </div>

    </Section>
</template>