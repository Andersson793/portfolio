<script>
import ContactSection from './contactSection.vue';
import FistSection from './fistSection.vue';
import FreelaSection from './freelaSection.vue';
import KnowledgeSection from './knowledgeSection.vue';
import ProjectsSection from './projectsSection.vue';

export default {
    components:{
    FistSection,
    KnowledgeSection,
    ProjectsSection,
    ContactSection,
    FreelaSection
}
}
</script>
<template>
    <main>
        <FistSection/>
        <KnowledgeSection/>
        <ProjectsSection/>
        <FreelaSection/>
        <ContactSection/>
    </main>
</template>
