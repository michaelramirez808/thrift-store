<template>
    <header>
        <h1>My Website</h1>
        <nav>
            <ul>
                <li><router-link to ='/'>Home</router-link></li>
                <li><router-link to = '/'>About</router-link></li>
                <li><router-link to = '/'>Store</router-link></li>
            </ul>
        </nav>
    </header>
</template>
<script setup>
import { defineComponent } from 'vue';

defineComponent({
    name: 'AppHeader',
});

</script>