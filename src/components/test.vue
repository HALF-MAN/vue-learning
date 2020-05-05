<template>
    <h2 class="red">
        {{msg}}
    </h2>
</template>

<style scoped>
    .red{
        color: red;
    }
</style>

<script>
export default {
    name: 'test',
    props: {
        msg:{
            type: String,
            default: "test msg"
        }
    },
    methods:{

    },
    data() {
        return {

        }
    }
}
</script>