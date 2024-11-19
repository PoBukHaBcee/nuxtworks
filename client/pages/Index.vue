<template>
    <div>
        <h2>Главная страница</h2>
    </div>
    <main>
        <article v-for="post in posts" :key="post.id">
            {{ post }}
        </article>
        
    </main>
</template>

<script setup>
    function contactform(){
        $fetch('/posts',{
            method: 'POST',
            body: {posts: "world"}
        })
    }
</script>