<template>
    <div>
        <h1>Todos</h1>
        <ul v-for="item in todos" v-bind:key="item.id">
            <li>{{item.title}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'Todos',
    props: [
        'todos'
    ]
}
</script>

<style scoped>

</style>