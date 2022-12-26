<script lang="ts">
  import '../style/main.scss'
  import Nav from '$lib/components/Nav.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>


<header>
<Nav/>
</header>

<main>
  
  
  <slot/>

  
</main>

<div class="footer">
  <Footer/>
</div>


<style lang="scss">
  header {
    height: 6rem;
    display: flex;
    align-items: center;
    justify-content: center;
    // border: 1px solid;
    background-color: var(--primary-color);
    padding: 0 3rem;
  }

  main {
    height: 100%;
    width: 100vw;
    overflow-x: hidden;
    
  }


  .footer {
    height: 18rem;
    width: 100%;
    background-color: var(--secondary-color);
    padding: 0 16rem;
  }
</style>