<template>
    <v-footer height="auto" color="white">
        <v-layout justify-center row wrap>
            <v-btn v-for="link in links" :key="link" color="primary" flat round>
                {{ link }}
            </v-btn>
            <v-flex white py-3 text-xs-center primary--text xs12>
                &copy;2019 — <strong>Felipe Kosouski</strong>
            </v-flex>
        </v-layout>
    </v-footer>
</template>

<script>
    export default {
        data: () => ({
            links: [
                'Github',
                'LinkedIn'
            ]
        })
    }
</script>

<style scoped>

</style>