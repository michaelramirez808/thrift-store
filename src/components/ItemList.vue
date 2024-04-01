<template>
    <div>
        <h2>Item List</h2>
        <ul>
            <li v-for="item in items" : key="item.id">{{ item.name }}</li>
        </ul>
    </div>
</template>
<script setup>
import { defineProps } from 'vue';

const props = defineProps({
    items: {
        type: Array,
        required: true,
    },
});

</script>