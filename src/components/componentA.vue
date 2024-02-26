<template>
<p>Hello Vue</p>
{{ data }}

<p>--</p>
<input type="text" v-model="text">
<p>{{ text }}</p>
</template>



<script setup>
import { ref } from 'vue';

const data = "hello Vue 3";
const text = ref("555");
</script>



<style>

</style>
