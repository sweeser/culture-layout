<template>
    <section class="advertisement">
        <img class="advertisement__image" :src="require('@/assets/icon-mountain.svg')" alt="">
        <h2 class="advertisement__title">Подводный отель</h2>
        <p class="advertisement__description">Как известно, Дубай – город контрастов. Самые революционные и фантастические мечты архитекторов способен воплотить в жизнь этот мегаполис, построенный на нефти и за счет нефти</p>
    </section>
</template>

<script>
export default {
    name: 'AdvertismentComponent'
};
</script>

<style src="@/styles/advertisment.css"></style>