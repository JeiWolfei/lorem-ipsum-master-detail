<template>
  <li>
    <p>Title: {{ ipsum.title }}</p>
    <p>Category: {{ ipsum.category }}</p>
  </li>
</template>

<script>
export default {
  props: {
    ipsum: Object
  }
};
</script>

<style>
  li {
    border: 3px solid rgb(30, 76, 230);
    padding: 10px;
    margin-bottom: 10px;
  }
</style>