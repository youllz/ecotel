<script>
	import Btn from "./Btn.svelte";

</script>

<section id="prestaions">
  <h1>PRESTATION</h1>
  <div class="pt-dej prestration_container ">
   
    <div class="pt-dej_right img-container">
      <img src="/pt-dej.png" alt="">
    </div>
    <div class="pt-dej_left description">
      <h2>DEJENER D'AFFAIRE</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium error esse earum, voluptatum, aliquam asperiores obcaecati quisquam et reiciendis quis incidunt voluptatem ullam a laboriosam nostrum. Nobis quisquam quaerat voluptatibus?
      </p>
      <a href="/prestations/dejeuner-daffaire">
        <Btn>
          EN SOVOIR PLUS
        </Btn>
      </a>
    </div>
  </div>
  <div class="prestration_container">

    <div class="description">
      <h2>CANTINE</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut, magni inventore nam nostrum neque est laudantium veritatis ipsam fugit alias ullam esse molestias sed! Sunt voluptates totam corporis dolorum obcaecati!</p>
      <a href="/prestations/cantine">
        <Btn>
          EN SOVOIR PLUS
        </Btn>
      </a>
    </div>
    <div class="img-container">
      <img src="/cantine.png" alt="">
    </div>

  </div>
  <div class="prestration_container">

    <div class="img-container">
      <img src="/party.png" alt="">
    </div>
    <div class="description">
      <h2>CEREMONIE</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut, magni inventore nam nostrum neque est laudantium veritatis ipsam fugit alias ullam esse molestias sed! Sunt voluptates totam corporis dolorum obcaecati!</p>
      <Btn>
        EN SOVOIR PLUS
      </Btn>
    </div>

  </div>
  
</section>



<style lang="scss">

section {
  height: 100%;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  gap: 3rem;
  margin-top: 10rem  ;
}


h1 {
  font-size: 3rem;
  color: var(--headline);
}





.pt-dej, .prestration_container {
  height: 25%;
  width: 100%;
  display: flex;
  gap: 3rem;
  margin-top: 5rem;

}


.pt-dej_right {
  background-image: url('/blob_1.svg');
  background-position: center;
  background-size: contain;

}

.description, .img-container {
  height: 30%;
  width: 100%;
}


.description {
  display: flex;
  flex-direction: column ;
  justify-content: space-around;
  padding-left: 10rem;
  height: 100%;
  gap: 5rem;
  padding-top: 3rem;


  h2 {
    color: var(--secondary-color);
    font-size: 1.5rem;
  }

  p {
    font-size: 1.6rem;
    line-height: 1.5;
  }

}


</style>