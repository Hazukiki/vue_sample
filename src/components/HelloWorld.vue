<template>
    <div class="my-component">
        <button @click= "onClick">{{message}}</button>
    </div>
</template>

<style lang="scss" scoped>
    .my-component {
        color: #555;
        button {
            border: 1px solid #555;
            font-size: 40px;
        }
    }
</style>

<script>
    export default {
        data() {
            return {
                message: 'NewThread'
            }
        },
        methods: {
            onClick() {
                console.log(this.message)
            }
        }
    }
</script>
