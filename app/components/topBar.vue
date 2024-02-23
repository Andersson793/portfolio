<script>

export default {
    data(){
        return {
            count: 0,
            isOpen: false,
        }
    }
}

</script>
<template>
    <div class="grid grid-cols-2 mx-28:sm py-6 px-6">

        <a class="justify-self-start" href="https://andersson.vercel.app/">
            <img class="h-8" src="/andersson.svg" alt="Andersson">
        </a>

        <div class="inline-flex items-center justify-self-end justify-items-end">

            
            <div @click="isOpen = !isOpen" class="sm:hidden ml-14 cursor-pointer px-3 py-1">
                <img  class="h-7 min-w-fit" src="/menu.svg" alt="menu">
            </div>

            <div v-if="isOpen" style="background: rgb(0, 31, 1)" class="absolute grid  grid-cols-1 gap-y-1.5 right-5 top-5 h-auto rounded-md text-center p-1.5 z-10">
                <div class="py-4 text-2xl cursor-pointer" @click="isOpen = !isOpen">
                    X
                </div>
                <a href="https://github.com/Andersson793" class="bg-slate-100/5 rounded-md py-2 px-5">
                    Github
                </a>
                <a href="https://www.linkedin.com/in/andersson-silva-gon%C3%A7alves-2a6839203/" class="bg-slate-100/5 rounded-md py-2 px-5">
                    Linkedin
                </a>
                <a href="https://br.fiverr.com/andersson793/developer-you-personal-website" class="bg-slate-100/5 rounded-md py-2 px-5">
                    Freelancer
                </a>
                <a href="#contato" class="bg bg-slate-100/5 rounded-md py-2 px-5">
                    Contato
                </a>
            </div>


            <div class="hidden sm:block">
                <nav class="grid grid-cols-4 justify-items-center gap-3 font-bold">
                    <a class="hover:bg-slate-100/5 rounded-md py-2 px-5" href="#contato">Contato</a>
                    <a class="hover:bg-slate-100/5 rounded-md py-2 px-5" href="https://www.linkedin.com/in/andersson-silva-gon%C3%A7alves-2a6839203/">Linkedin</a>
                    <a class="hover:bg-slate-100/5 rounded-md py-2 px-5" href="https://github.com/Andersson793">GitHub</a>
                    <a class="hover:bg-slate-100/5 rounded-md py-2 px-5" href="https://br.fiverr.com/andersson793/developer-you-personal-website">Freelancer</a>
                </nav>
            </div>

        </div>
        
    </div>
</template>