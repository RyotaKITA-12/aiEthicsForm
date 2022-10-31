<template>
    <v-app>
        <Nav />
        <v-main>
            <Home />
        </v-main>
    </v-app>
</template>

<script>
import Nav from '@/components/layouts/Nav'
import Home from '@/views/Home'

export default {
    name: 'App',
    components: {
        Nav,
        Home,
    },
};
</script>
