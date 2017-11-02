<template>
  <div class="page">
    <get-todo></get-todo>
    <current-todos></current-todos>
    <completed-todos></completed-todos>
  </div>
</template>

<script>
import GetTodo from 'components/GetTodo'
import CurrentTodos from 'components/CurrentTodos'
import CompletedTodos from 'components/CompletedTodos'

export default {
  components: {
    GetTodo,
    CurrentTodos,
    CompletedTodos
  }
}
</script>
