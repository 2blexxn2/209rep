<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
	<!-- 	<img src="../assets/pic1.jpg" alt="Girl in a jacket" width="1000" height="600">
 -->
	<!-- 	<table>
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
		<tr>
			<td>2</td>
			<td colspan="4">Мова програмування Python</td>
		</tr>
		<tr>
			<td>3</td>
			<td colspan="4">
				<table>
					<tr class="red-line">Людино-машинна взаємодія</tr><br>
					<tr class="red-line">Людино-машинна взаємодія</tr>
				</table>
			</td>
		</tr>
	</table> -->
	<table>
		<tr style="background-color: #212222;" >
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
			<td colspan="4">None/Емпіричні методи програмної інженерії проф. Швед А.В</td>
		</tr>
		<tr>
			<td>2</td>
			<td colspan="4">Мова програмування Python</td>
		</tr>
		<tr>
			<td colspan="1">3</td>
			<td colspan="8">
				<table class="first">
					<tr class="red-line">
						<td style="border: blue;">Людино-машинна взаємодія</td>
					</tr>
					<tr>
						<td style="border: blue;">ОБД</td>
					</tr>
					<tr>
						<td style="border: blue;"></td>
					</tr>
				</table>
			</td>
		</tr>
		<tr>
			<td>4</td>
			<td colspan="4">ООП</td>
		</tr>
		<tr>
			<td>5</td>
			<td colspan="4"></td>
		</tr>
		<tr>
			<td rowspan="5">Середа</td>
			<td>1</td>
			<td colspan="4"></td>
		</tr>
		<tr>
			<td>2</td>
			<td colspan="2">Іноземна мова</td>
			<td colspan="2">Іноземна мова</td>
		</tr>
		<tr>
			<td>3</td>
			<td colspan="2">ООП</td>
			<td colspan="2">ЛМВ</td>
		</tr>
		<tr>
			<td>4</td>
			<td colspan="4">Емпіричні методи програмної інженерії</td>
		</tr>
		<tr>
			<td>5</td>
			<td colspan="2"></td>
			<td colspan="2">ООП</td>
		</tr>
		<tr>
			<td rowspan="5">Четвер</td>
			<td>1</td>
			<td colspan="2"></td>
		</tr>
		<tr>
			<td>2</td>
			<td colspan="2"></td>
			<td colspan="2"></td>
		</tr>
		<tr>
			<td>3</td>
			<td colspan="2"></td>
			<td colspan="2"></td>
		</tr>
		<tr>
			<td>4</td>
			<td colspan="2"></td>
			<td colspan="2"></td>
		</tr>
		<tr>
			<td>5</td>
			<td colspan="2"></td>
			<td colspan="2"></td>
		</tr>
		<tr>
			<td rowspan="6">П'ятниця</td>
		</tr>
		<tr>
			<td colspan="1">1</td>
			<td colspan="8">
				<table class="first">
					<tr class="red-line">
						<td style="border: blue;"> Лекції SPA-технології доц. Давиденко Є.О</td>
					</tr>
					<tr>
						<td style="border: blue;">None</td>
					</tr>
					<tr>
						<td style="border: blue;"></td>
					</tr>
				</table>
			</td>
		</tr>
		<tr>
			<td>2</td>
			<td colspan="4">Практичні SPA-технології 1-ша підгрупа</td>
		</tr>
		<tr>
			<td>3</td>
			<td colspan="4">Практичні SPA-технології 2-га підгрупа</td>
		</tr>
		<tr>
			<td>4</td>
			<td colspan="4"></td>
		</tr>
				<tr>
				<td>5</td>
				<td colspan="4"></td>
			</tr>
	</table>
</template>

<style>
table,
th,
td {
	border: 1px solid white;
	border-collapse: collapse;
	text-align: center;
}

.red-line {
	border-bottom: 1px solid white;
}

.first {
	border: none;
	width: 550px;
}
</style>
