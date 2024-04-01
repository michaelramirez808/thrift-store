<template>
    <div>
        <h2>Item Details</h2>
        <div>
            <h3>{{ item.name }}</h3>
            <p>{{ item.description }}</p>
            <h4>{{ item.price }}</h4>
        </div>
    </div>
</template>

<script setup>
import {defineProps} from 'vue';

const props = defineProps({
    item: {
        type: Object,
        require: true,
    },
});

</script>