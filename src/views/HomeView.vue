<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
<!-- 	<img src="../assets/pic1.jpg" alt="Girl in a jacket" width="1000" height="600">
 -->
	<table>
	  <tr>
	    <th>День</th>
	    <th>Пара</th>
	    <th colspan="2">Підгрупа А</th>
	    <th colspan="2">Підгрупа Б</th>
	  </tr>
	  <tr>
	    <td rowspan="5">Понеділок</td>
	    <td>1</td>
	    <td colspan="2">Людино-машинна взаємодія</td>
	    <td colspan="2"></td>
	  </tr>
	  <tr>
	    <td>2</td>
	    <td>Організація баз даних</td>
	    <td>Мова програмування Python</td>
	    <td>Мова програмування Python</td>
	    <td>Організація баз даних</td>
	  </tr>
	  <tr>
	    <td>3</td>
	    <td colspan="2">Обд</td>
	    <td colspan="2">Обд</td>
	  </tr>
	  <tr>
	    <td>4</td>
	    <td colspan="2">Мова програмування Python</td>
	    <td colspan="2">Мова програмування Python</td>
	  </tr>
	  <tr>
	    <td>5</td>
	    <td colspan="2"></td>
	    <td colspan="2"></td>
	  </tr>
		 <tr>
		    <td rowspan="5">Вівторок</td>
		    <td>1</td>
		    <td colspan="4">Емпіричні методи програмної інженерії проф. Швед А.В</td>
		  </tr>
	</table>
 </template>
 
<style>
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}

</style>