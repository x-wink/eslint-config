<template>
    <div>
        <a href="https://vitejs.dev" target="_blank">
            <img alt="Vite logo" class="logo" src="/vite.svg" />
        </a>
        <a href="https://vuejs.org/" target="_blank">
            <img alt="Vue logo" class="logo vue" src="./assets/vue.svg" />
        </a>
    </div>
    <HelloWorld msg="Vite + Vue" />
</template>
<script setup lang="ts">
    import HelloWorld from './components/HelloWorld.vue';
</script>
<style scoped>
    .logo {
        height: 6em;
        padding: 1.5em;
        will-change: filter;
        transition: filter 300ms;
    }
    .logo:hover {
        filter: drop-shadow(0 0 2em #646cffaa);
    }
    .logo.vue:hover {
        filter: drop-shadow(0 0 2em #42b883aa);
    }
</style>
