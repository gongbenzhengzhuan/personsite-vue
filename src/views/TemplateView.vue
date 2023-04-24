<template>
    <h1>{{ message }}</h1>
    <div>
        <input type="checkbox" id="todo-item" checked="false" />
        <label for="todo-item">My Todo Item</label>
    </div>
</template>

<script lang="ts">
export default {
  data() {
    return {
      message: 'Hello World!,我的从js传入的值'
    }
  }
}
</script>

<style scoped>

</style>