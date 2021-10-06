<template>
  <li>
    <a class="text-capitalize pb-3" :class="{active : element.active}" :href="element.url">
        {{ element.name }}
    </a> 
  </li>
</template>

<script>
export default {
name : 'MainNavbar',
props : ['element']
}
</script>

<style>
.active{
  color: red;
  border-bottom: 2px solid red;
}
</style>