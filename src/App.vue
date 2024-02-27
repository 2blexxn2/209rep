<script setup lang="ts">
import Navbar from "./components/Navbar.vue";
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
	<Navbar />
	<header>
		<div class="menu">
			<img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="100" height="100" />
			<div class="wrapper">
				<!-- 			<HelloWorld msg="ФКН" style="margin-top: 50px;"/>
			<HelloWorld msg="ІПЗ" style="padding-top: 50px;"/> -->
				<h1>IPZ 209</h1>
				<nav class="nav1">
					<RouterLink to="/">Розклад</RouterLink>
					<RouterLink to="/about">Викладачі</RouterLink>
				</nav>
			</div>
		</div>
	</header>

	<RouterView />
</template>

<style scoped>
h1 {
	color: rgb(7, 153, 80);
	font-weight: bold;
}

.menu {
	display: flex;
	justify-content: center;
	align-items: center;
}

header {
	padding-top: 50px;
	display: flex;
	align-content: center;
	justify-content: center;
	align-items: center;
	width: 100%;
	/* Змінено на 100% */
}

.logo {
	display: flex;
	justify-content: center;
	align-items: center;
}

.nav1 {
	width: 100%;
	font-size: 12px;
	text-align: center;
	margin-top: 2rem;
}

.nav1 a.router-link-exact-active {
	color: var(--color-text);
}

.nav1 a.router-link-exact-active:hover {
	background-color: transparent;
}

.nav1 a {
	display: inline-block;
	padding: 0 1rem;
	border-left: 1px solid var(--color-border);
}

.nav a:first-of-type {
	border: 0;
}

@media (min-width: 1024px) {
	header {
		display: flex;
		place-items: center;
		padding-right: calc(var(--section-gap) / 2);
	}

	.logo {
		margin: 0 2rem 0 0;
	}

	header .wrapper {
		display: flex;
		flex-wrap: wrap;
	}

	.nav1 {
		text-align: left;
		margin-left: -1rem;
		font-size: 1rem;

		padding: 1rem 0;
		margin-top: 1rem;
	}
}
</style>
