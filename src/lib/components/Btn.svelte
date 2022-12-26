<button>
  <slot></slot>
</button>


<style lang="scss">

  button {
    height: 5rem;
    width: 15rem;
    background-color: var(--secondary-color);
    outline: none;
    cursor: pointer;
    font-size: 1.4rem;
    font-weight: 700;
    transition: all 0.3s ease;
    border: none;
    color: var(--text);

    
  }

  button:hover {
    background-color: #f45c48a6;
  }

</style>