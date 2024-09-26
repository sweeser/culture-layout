<template>
    <section class="service">
        <h2 class="service__title">Абонементы в театр</h2>
        <ul class="service__list">
            <li class="service__item">
                <h3 class="service__item-title">Скидка 50% на весь сезон 2020</h3>
                <p class="service__item-description">Покупая абонемент на сезон 2020 года вы сэкономите половину стоимости всех спектаклей</p>
            </li>
            <li class="service__item">
                <h3 class="service__item-title">Места у сцены</h3>
                <p class="service__item-description">Только для обладателей абонементов будет возможность сесть поближе к сцене</p>
            </li>
            <li class="service__item">
                <h3 class="service__item-title">Автограф-сессия актёров</h3>
                <p class="service__item-description">После спектаклей у вас будет возможность пообщаться с актёрами и взять у них автограф</p>
            </li>
        </ul>
        <a href="#" class="service__button">Смотреть<img class="service__button-image" :src="require('@/assets/Arrow forward.svg')" alt=""></a>
    </section>
</template>

<script>
export default {
    name: 'ServiceComponent'
};
</script>

<style src="@/styles/service.css"></style>