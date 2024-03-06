<script setup>
import HeaderCash from './HeaderCash.vue';
import LayoutCash from './LayoutCash.vue';
import Resume from './Resume/ResumeIndex.vue';
import MovementsCash from './MovementsCash.vue';
</script>

<template>
    <LayoutCash>
        <template #header>
            <HeaderCash></HeaderCash>
        </template>
        <template #resume>
            <Resume></Resume>
        </template>
        <template #movements>
            <MovementsCash></MovementsCash>
        </template>
    </LayoutCash>
</template>