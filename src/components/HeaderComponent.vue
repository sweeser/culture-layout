<template>
    <header class="header">
        <h1 class="header__title">Новости культуры</h1>
        <nav class="navigation">
            <ul class="navigation__list">
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Новости</a>
                </li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Обзоры</a>
                </li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Музыка</a>
                </li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Архитектура</a>
                </li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Кино</a></li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Театр</a>
                </li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Литература</a>
                </li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Религия</a>
                </li>
                <li class="navigation__item">
                    <a class="navigation__item-link" href="#">Живопись</a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent'
};
</script>

<style src="@/styles/header_styles.css"></style>