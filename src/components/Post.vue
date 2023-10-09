<script>
    export default {
        name: 'Post'
    }
</script>

<template>
    <div>
        <h1>Posts</h1>
        <router-link :to="'/post/${$route.params.id}/comments'">View Comments</router-link>
        <router-view></router-view>
    </div>
</template>