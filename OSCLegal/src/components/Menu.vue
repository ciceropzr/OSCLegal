<template>
	<section>
		<div class="logo-menu">
			<img src="../assets/Logo-OSC-15.svg" alt="Logo OSC Legal">
		</div>
		<div class="menu">
			<ul>
				<li>BLOG</li>
				<li>SOBRE</li>
				<li>SERVICOS</li>
				<li>MAPEAMENTO</li>
				<li>LINKS</li>
				<li>CONTATO</li>
			</ul>
		</div>
	</section>
</template>
<script>
	export default {
  		name: 'Home',
  		data () {
    		return {
      
    		}
  		}
	}
</script>
<style scoped>

.logo-menu {
	display: flex;
	justify-content: center;
}

section {
	display: flex;
	align-items: flex-end;
	width: 100%;
	min-height: 100%;
	margin: 3vh 
}

img {
	width: 100%;
}

.menu {
	display: flex;

	width: 60%;
}

ul {
	display: flex;
	flex-wrap: nowrap;
	justify-content: space-around;
	align-content: flex-end;
	width: 100%;
	padding: 0;
	margin-bottom: 0
}	

li {
	list-style: none;
}
</style>