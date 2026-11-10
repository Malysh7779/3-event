<script setup>
import Button from "./Button.vue";
import Heart from "./Heart.vue";
</script>

<template>
    <div class=header>
        <h2>Запомни слово</h2>
        <Button>
            10
            <Heart />
        </Button>
    </div>
</template>

<style scoped>
.header {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 38px 60px;
    height: auto;
}
h2 {
    text-transform: uppercase;
}
</style>

