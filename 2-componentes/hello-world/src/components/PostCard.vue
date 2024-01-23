<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident explicabo fugiat earum numquam a minus et vitae doloremque facere quos alias dolorem dolorum, suscipit ratione! Exercitationem molestias quidem fugit debitis!</p>
        <PostButton />
    </div>
</template>

<script lang="ts" setup>
    import PostButton from './PostButton.vue'
</script>

<style scoped>
.post-card {
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>