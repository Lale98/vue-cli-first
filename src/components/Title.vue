<template>
    <h1> {{msg}} </h1>
</template>

<script>
export default {
    name: 'Tilte',
    props: {
        msg: String
    }
}
</script>



<style scoped lang="scss">
    h1 {
        margin: 50px 0;
    }
</style>
