<template>
	<section>
		<div class="noticiaprincipal">
			<div class="noticiaprincipaltitulo">
				<samp>Texto</samp>
				<h1>Os conselhos de políticas públicas no MROSC</h1>
				<p>por Lucas Seara</p>
			</div>
			<div class="noticiaprincipaltexto">
				<p>O novo marco regulatório das parcerias estabelecidas entre a Administração Pública e as Organizações da Sociedade Civil (Lei no 13.019, de 31 de julho de 2014, e sua regulamentação), conhecido como MROSC, tem como fundamentos a gestão pública democrática, a participação social e o fortalecimento da sociedade civil.</p>
				<samp>leia mais</samp>
			</div>
		</div>
		<div class="noticiasecundaria">
			<div class="noticiasecundariaitem1">
				<div>
					
				</div>
			</div>
			<div class="noticiasecundariaitem2">
				<div>
					
				</div>
			</div>
		</div>
	</section>	
</template>

<script>
	
</script>

<style scoped>

section {
	display: flex;
	justify-content: space-around;
	align-items: center;
	background-color: rgb(248, 78, 54);
	min-height: 100%
}

.noticiaprincipal {
	height: 50vh;
	width: 40vh;
	background-color: rgb( 256, 256, 256);
	padding: 2%;
}

.noticiaprincipaltitulo {
	margin-bottom: 10%
}

.noticiasecundaria{
	display: flex;
	justify-content: space-between;
	width: 77.5vh
}

.noticiasecundariaitem1 {
	height: 50vh;
	width: 37.5vh;
	background-color: rgba( 256, 256, 256, 0.7);
}

.noticiasecundariaitem2 {
	height: 50vh;
	width: 37.5vh;
	background-color: rgba( 256, 256, 256, 0.7);
}

</style>