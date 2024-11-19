<template>
    <header>
        <nav>
            <ul>
                <li><nuxtLink to="/">Home</nuxtLink></li>
                <li><nuxtLink to="/about">About</nuxtLink></li>
                <li><nuxtLink to="/contact">Contact</nuxtLink></li>
            </ul>
        </nav>
    </header>
</template>

<script setup>
</script>

<style scoped>
    ul {
        display: flex;
        gap: 10px;
        list-style: none;
    }
</style>