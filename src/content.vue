<template>
    <div class="lunzi-content">
        <slot></slot>
    </div>
</template>

<script>
    export default {
        name: 'lunziContent'
    }
</script>

<style lang="scss" scoped>
    .lunzi-content {
        flex-grow: 1;
    }
</style>