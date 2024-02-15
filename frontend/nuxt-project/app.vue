<template>
  <div>
    <p>{{data}}</p>
  </div>
</template>

<script setup>
    const {data} = await useFetch('http://sample_project_nginx:9000/api/check');
</script>