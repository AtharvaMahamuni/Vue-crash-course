<template>
<h1>Hello from TODO list template</h1>
</template>

<script>
    export default{
        data() {
            return {
                todos: [
                    {
                        id: 1,
                        title: 'Learn Vue',
                        completed: true
                    },
                    {
                        id: 2,
                        title: 'Learn Vuex',
                        completed: false
                    },
                    {
                        id: 3,
                        title: 'Learn Vue Router',
                        completed: false
                    }
                ]
            }
        },
        methods: {
            addTodo() {},
            toggleTodo() {},
            editTodo() {},
            deleteTodo() {}
        }
    };
</script>

<style>
</style>