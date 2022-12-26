<script>
	import Btn from "$lib/components/Btn.svelte";

</script>
<section>
	<div class="banner">
		<div class="left">
			<h1>
				Bienvenue sur notre page <br /> dédiée aux petits déjeuners d'affaire !
			</h1>
		</div>
	</div>

  <div class="description-1">
    <p>
      Notre sélection de petits déjeuners d'affaire inclut des options de croissants et de viennoiseries,  des jus de fruits frais et bien plus encore. Nous avons également une sélection de boissons chaudes et froides, y compris du café de qualité supérieure et du thé de qualité supérieure.
    </p>
  </div>

  <div class="img-box">
    <div class="img"><img src="/petit-dej.png" alt=""></div>
  </div>

  <div class="description-2">
    <p>
      Nous sommes impatients de vous accueillir et de vous offrir un début de journée parfait pour votre prochain événement d'affaires. N'hésitez pas à nous contacter pour plus d'informations ou pour réserver votre petit déjeuner d'affaire. Nous nous réjouissons de vous servir bientôt !
    </p>
  </div>

  <a href="/contacts">
    <Btn>
      CONTACTER NOUS
    </Btn>
  </a>
</section>

<section class="gallerie-container">
  <div class="separateur"></div>

  <div class="galleries">
    <ul>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
      <li><img src="https://via.placeholder.com/150" alt=""></li>
    </ul>
  </div>
</section>

<style lang="scss">
	section {
		padding-top: 5rem;
    
	}

	.banner {
		width: 100%;
		height: 25%;
		// background-color: red;

		h1 {
			font-size: 3rem;
			color: var(--headline);
		}
	}

	.left {
		background-image: url('/blob_2.svg');
		background-repeat: no-repeat;
		background-position: left;
		background-size: contain;
		width: 50%;
		height: 100%;
		display: flex;
		align-items: center;
	}

  .description-1 {
    display: flex;
    align-items: center;
    height: 25%;
    width: 50%;


    p {
      font-size: 1.7rem;
      font-weight: 700;
      line-height: 1.3;
      color: var(--text);
    }
    
  }

  .img-box {
    height: 25%;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    width: 100%;
    // background-color: red;
    

    .img {
      width: 50%;
      height: 100%;

    }

    img {
      object-fit: contain;
    }

  }
    .description-2 {
      display: flex;
    align-items: center;
    height: 25%;
    width: 50%;


    p {
      font-size: 1.7rem;
      font-weight: 700;
      line-height: 1.3;
      color: var(--text);
    }
    
    }


    .gallerie-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    .separateur {
      height: 3px;
      width: 50%;
      background-color: var(--hightlight);
      margin: 5rem 0;
    }

    .galleries {
      height: 200vh;
      // background-color: red;
      overflow: scroll;
      padding: 2rem 0;
      margin: 0 14rem;
      overflow-x: hidden;

      ul {
        max-width: 1100px;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
        gap: 2vmin;
        background-color: aqua;


        li {
          height: 250px;
          flex-grow: 1;
        }
        
        img {
          width: 100%;
          height: 100%;
          object-fit: cover;
        }
        
      }
    }

</style>
