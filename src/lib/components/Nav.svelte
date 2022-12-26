<nav>
  <div class="logo">
    <svg width="32" height="32" viewBox="0 0 24 24"><path fill="none" stroke="#078080" stroke-width="2" d="M19 18H5h14Zm-7 0v-6v6Zm3 0v-4v4Zm-6 0v-4v4Zm10 4V11.33a3.001 3.001 0 1 0-2.08-5.63C16.55 3.874 14.46 2 12 2S7.45 3.874 7.08 5.7A3 3 0 1 0 5 11.33V22h14Z"/></svg>
  </div>

  <ul>
    <li><a href="/">Acceuil</a></li>
    <li><a href="#prestations">Prestation</a></li>
    <li><a href="/gallerie">Gallerie</a></li>
    <li><a href="/contacts">Contacts</a></li>
  </ul>
</nav>


<style lang="scss">

  nav {
    height: 3rem;
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: var(--primary-color);
  }

  ul{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 2.5rem;

  }
  
  a {
   color: var(--headline);
   text-decoration: none;
   font-size: 2rem;
   font-weight: 600;
   transition: all 0.3s ease;
   
  }

  a:hover {
    color: var(--hightlight);
  }
</style>