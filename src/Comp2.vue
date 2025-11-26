<script setup>
defineProps({
    disabled: {
        type: Boolean,
        default: false
    }
})


</script>

<template>
    <div>
        {{ disabled }}
        <button :disabled="disabled">Кнопка</button>
    </div>
</template>