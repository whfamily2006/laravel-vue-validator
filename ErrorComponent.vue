<template>
    <div v-if="$errors.has(input)" class="alert-error">
        {{ $errors.first(input) }}
    </div>
</template>
<script>

    export default {

        props: ['input'],

        data(){
            return {}
        },

        methods: {},

        computed: {},

        watch: {},

        mounted(){

        }
    }

</script>