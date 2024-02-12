<script>
import Section from './micro/section.vue';
import SubTitles from './micro/subTitles.vue';

export default {
    components : {
    SubTitles,
    Section
}
}
</script>
<template>
    <Section>
        <SubTitles>
            Precisa de um freelancer ?
        </SubTitles>

        <p class="text-center ">Faça o seu novo site pessoal, ou da sua empresa.</p>

        <div class="text-center p-24">
            <div itemscope itemtype='http://schema.org/Person' class='fiverr-seller-widget' style='display: inline-block;'>
                <a itemprop='url' href=https://www.fiverr.com/andersson793 rel="nofollow" target="_blank" style='display: inline-block;'>
                    <div class='fiverr-seller-content' id='fiverr-seller-widget-content-effa7374-dd29-4623-87b7-92fb96d136bb' itemprop='contentURL' style='display: none;'></div>
                    <div id='fiverr-widget-seller-data' style='display: none;'>
                        <div itemprop='name' >andersson793</div>
                        <div itemscope itemtype='http://schema.org/Organization'><span itemprop='name'>Fiverr</span></div>
                        <div itemprop='jobtitle'>Seller</div>
                        <div itemprop='description'>Sou um programdor front-end tenho formação superior na área de análise e desenvolvimento de sistemas, sou apaixonado por programação, tenho alguns projetos pessoais no meu github onde compartilho um pouco da minha experiência.</div>
                    </div>
                </a>
            </div>
        </div>
    </Section>
    <!-- Put this code anywhere in the body of your page where you want the badge to show up. -->
</template>