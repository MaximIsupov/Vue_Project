<template>
    <div>
        {{todos}}
       <TodoItem
       v-for="todo of todos"
       v-bind:todo="todo"
       v-bind:key=todo.id
       />
    </div>
</template>

<script>
import TodoItem from '@/components/TodoItem'
export default {
    props:['todos'],
    components: {
        TodoItem
    }
}
</script>

