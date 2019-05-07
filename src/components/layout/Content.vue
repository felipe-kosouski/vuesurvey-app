<template>
    <div>
        <v-layout row justify-space-between>
            <new-button></new-button>
            <search></search>
        </v-layout>
        <survey-card id="card"></survey-card>
    </div>
</template>

<script>
import NewButton from '../surveys/New.vue'
import Search from '../surveys/Search.vue'
import SurveyCard from '../surveys/Card.vue'

export default {
    components: {
        NewButton,
        Search,
        SurveyCard
    }
}
</script>

<style scoped>
#card{
    margin-top: 3em;
}
</style>