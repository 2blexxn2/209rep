<script setup lang="ts">
import Navbar from "./components/Navbar.vue";
import { RouterLink, RouterView } from "vue-router";
// import Calls from "./components/Calls.vue";
</script>

<template>
	<Navbar />
	<header>
		<div class="menu">
			<div class="wrapper">
				<h1>IPZ 309</h1>
				<nav class="nav1">
					<RouterLink to="/" class="nav-button">Розклад</RouterLink>
					<RouterLink to="/about" class="nav-button">Викладачі</RouterLink>
				</nav>
				<!-- <Calls /> -->
			</div>
		</div>
	</header>

	<RouterView />
</template>

<style scoped>
h1 {
	color: rgb(7, 153, 80);
	font-weight: bold;
	font-size: 2.5rem; 
	margin-bottom: 1rem; 
	text-align: center;
}

.menu {
	display: flex;
	justify-content: center;
	align-items: center;
	padding: 2rem 0; 
	width: 100%;
}

header {
	display: flex;
	justify-content: center;
	align-items: center;
	width: 100%;
	background-color: #000000; 
}

.wrapper {
	display: flex;
	flex-direction: column; 
	align-items: center; 
	width: 100%;
}

.nav1 {
	font-size: 1.2rem; 
	text-align: center;
	margin-top: 1.5rem;
	background-color: #18171700; 
	border: 1px solid #fff;
	border-radius: 30px; 
	padding: 0.5rem; 
	box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); 
}

.nav-button {
	display: inline-block;
	padding: 0.7rem 1.5rem; 
	margin: 0 0.5rem; 
	border: none; 
	border-radius: 25px; 
	text-decoration: none; 
	color: #333; 
	background-color: rgb(7, 153, 80);
	transition: all 0.3s ease; 
	border: 2px solid #034119;
}

.nav-button:hover {
	background-color: #e0e0e0; 
	transform: translateY(-2px); 
}

.nav-button.router-link-exact-active {
	background-color: rgba(7, 153, 80, 0.123);
	color: #fff; 
	font-weight: bold; 
	border: 1px solid #fff;
}

@media (min-width: 1024px) {
	.menu {
		padding: 3rem 0; /* Збільшено відступи для великих екранів */
	}

	.nav1 {
		margin-top: 1rem; /* Додано відступ зверху */
	}
}
</style>
