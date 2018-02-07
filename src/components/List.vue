<template>
    <ul>
        <li v-for="item in items">
            {{ item }}
        </li>
    </ul>
  </template>

<!-- This works when the script is embedded in the Vue file -->
<!-- <script> -->
<!-- export default { -->
<!--   name: 'list', -->
<!--   props: [ -->
<!--     'items' -->
<!--   ] -->
<!-- } -->
<!-- </script> -->


<script src="./List.js"></script>
