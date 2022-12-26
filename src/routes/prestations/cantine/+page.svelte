<script>
  import Btn from "$lib/components/Btn.svelte";
</script>


<section>
  <div class="banner">
		<div class="left">
			<h1>
        Bienvenue sur la page de notre cantine !
			</h1>
		</div>
	</div>

  <div class="description-1">
    <p>
      Notre cantine est l'endroit idéal pour prendre une pause et se restaurer pendant votre journée de travail. Nous proposons une large gamme de plats chauds et froids, ainsi que des boissons pour tous les goûts.
    </p>
  </div>

  <div class="img-box">
    <div class="img"><img src="/cream.png" alt=""></div>
  </div>

  <div class="description-2">
    <p>  
      Nous avons à cœur de proposer des plats sains et nutritifs pour encourager nos employés et nos clients à prendre soin de leur santé. Nous travaillons également avec des fournisseurs locaux pour soutenir l'économie locale et proposer des produits frais et de qualité.
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
		background-image: url('/cantine-blob.svg');
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