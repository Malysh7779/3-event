<script setup>
</script>

<template>
    <button class="button">
        <slot />
        <div>
            <slot name="icon" />
        </div>
    </button>
</template>

<style scoped>
.button {
    background: var(--bg-button);
    color: var(--color-button);
    border: none;
    border-radius: 36px;
    padding: 6px 12px;
    font-family: var(--font);
    font-weight: 700;
    cursor: pointer;
    display: flex;
    gap: 10px;
    align-items: center;
    justify-content: center;
    width: 110px;
    height: 48px;
}
</style>
