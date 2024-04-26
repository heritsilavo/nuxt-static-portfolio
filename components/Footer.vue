<script setup>
    const showSendMessage=useshowSendMessage()
    function sendMessage() {
        showSendMessage.value=true    
    }
</script>

<template>
    <div class="col-12 d-flex flex-column align-items-center justify-content-between __footer_container__">
        <div class="d-flex flex-column align-items-center justify-content-end col-12 flex-grow-1">
            <div class="m-2 col-12 flex-wrap d-flex align-items-center justify-content-between">
                <span class="m-2 badge"> <span>Email :</span>     <span>heritsilavo4835@gmail.com</span> </span>
                <span class="m-2 badge"> <span>Tél :</span>       <span>+261342631778 / +261328007119</span> </span>
                <span class="m-2 badge"> <span>Linkedin :</span>  <span>heritsilavo ANDRIANTSILAVINA</span> </span>
                <span class="m-2 badge"> <span>Facebook :</span>  <span>heritsilavo ANDRIANTSILAVINA</span> </span>
            </div>

            <div class="m-2 col-12  d-none d-md-flex align-items-start justify-content-center ">
                <NuxtLink external to="/#_sec2_"> <span class="badge m-2 p-2 __footer_menu_link__">A propos de moi</span> </NuxtLink>
                <NuxtLink external to="/#_sec3_"> <span class="badge m-2 p-2 __footer_menu_link__">Mes projets</span> </NuxtLink>
                <NuxtLink external to="/#_sec4_"> <span class="badge m-2 p-2 __footer_menu_link__">Mes services</span> </NuxtLink>
            </div>
        </div>
        <div class="d-flex flex-column align-items-center justify-content-center col-12">
            <div class="col-10 col-sm-8 col-md-4 col-lg-3 mt-1 border"></div>
            Edité par Heritsilavo le 2024
        </div>
    </div>
</template>

<style scoped>
.__footer_container__{
    background: linear-gradient(#050014,#000000);
    color: whitesmoke;
}
.__footer_menu_link__{
    cursor: pointer;
    color: whitesmoke;
}
.__footer_menu_link__ a{
    text-decoration: none;
}
#message{
    background: transparent;
    color: whitesmoke
}
</style>