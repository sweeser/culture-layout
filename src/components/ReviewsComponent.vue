<template>
    <section class="reviews">
        <h2 class="reviews__title">Обзоры</h2>
        <ul class="reviews__list">
            <li class="reviews__item review">
                <img class="review__image" :src="require('@/assets/review-picture-1.jpg')" alt="Иллюстрация – «Шальные годы» Монпарнаса">
                <h3 class="review__title"><a class="review__link" href="#">«Шальные годы» Монпарнаса</a></h3>
                <p class="review__description">В Музее изобразительных искусств имени Пушкина с 29 сентября по 29 ноября проходит выставка «Шальные годы Монпарнаса»</p>
            </li>
            <li class="reviews__item review">
                <img class="review__image" :src="require('@/assets/review-picture-2.jpg')" alt="Иллюстрация – Анатомия за 30 секунд">
                <h3 class="review__title"><a class="review__link review__link--active" href="#">Анатомия за 30 секунд</a></h3>
                <p class="review__description">Сейчас, когда мир открыт нараспашку для человека и его познавательных изысканий, интерес к научно‑популярной литературе заметно вырос</p>
            </li>
            <li class="reviews__item review">
                <img class="review__image" :src="require('@/assets/review-picture-3.jpg')" alt="Иллюстрация – Сферические чудаки">
                <h3 class="review__title"><a class="review__link" href="#">Сферические чудаки</a></h3>
                <p class="review__description">Корреспондентам «Культурного обозревателя» посчастливилось побывать в театре «Сфера» на премьере спектакля «Чудаки и зануды»</p>
            </li>
        </ul>
    </section>
</template>

<script>
export default {
    name: 'ReviewsComponent'
};
</script>

<style src="@/styles/reviews.css"></style>