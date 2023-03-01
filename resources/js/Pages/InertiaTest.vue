<script setup>
import { Link } from '@inertiajs/inertia-vue3';
</script>

<template>
    Inertiaテストです。<br>
    <a href="/">aタグ</a><br>
    <Link href="/">Link経由です</Link><br>
    <Link :href="route('inertia.index')">名前付きルート</Link>
</template>

<style scoped>

</style>
