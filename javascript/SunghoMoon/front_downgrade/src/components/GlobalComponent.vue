<template>
    <button @click="addCounter">{{ counter }}</button>
</template>

<script>
export default {
    name: 'global-component',
    props: ['initialTest'],
    data () {
        return {
            counter: this.initialTest
        }
    },
    methods: {
        addCounter () {
            this.counter += 1
        }
    }
}
</script>
© 2021 GitHub, Inc.