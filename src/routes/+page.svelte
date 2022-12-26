<script lang="ts">
	import Btn from "$lib/components/Btn.svelte";
	import LodoBox from "$lib/components/LodoBox.svelte";
	import Prestation from "$lib/components/Prestation.svelte";


</script>

<section>
	<div class="banner-text">
		<h1>
			<span>Bienvenue</span> sur notre site de <span>restauration</span> et d'organisation <span>d'événements</span> ! Nous sommes heureux
			de vous <span>accueillir</span> et de vous aider à <span>planifier</span> votre prochain repas ou événement <span>inoubliable</span>.
		</h1>
		<Btn>
			CONTACTER NOUS
		</Btn>
	</div>
	<div class="banner-img">
		<img src="/banner.png" alt="human">
	</div>
</section>
<Prestation/>
<LodoBox/>

<style lang="scss">
	section {
		height: 100vh;
		width: 100%;
		display: flex;
		align-items: flex-start;
		padding-top: 3rem;
		background-color: #DFDBE5;

		div {
			width: 50%;
			height: 80%;
			display: flex;
			align-items: center;
			justify-content: center;
			padding: 2rem;
		}

		.banner-img {
			// background-color: red;

			img {
				height: 100%;
				width: 100%;
				object-fit: cover;
			}
		}

		.banner-text {
			display: flex;
			flex-direction: column;
			gap: 4rem;
			align-items: flex-start;
			
			h1 {
				text-align: start;
				font-size: 3rem;
				line-height: 1.2;
				color: var(--text);

				span {
					position: relative;
					text-decoration: underline solid  var(--secondary-color);
					// display: block;

					
				}
			}
		}
	}
</style>
