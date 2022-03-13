<script>
  import Counter from './lib/Counter.svelte'
  import TranistionButton from './lib/Transition.svelte'
</script>

<main>

  <h1>Hello world!</h1>

  <Counter text="Clicks"/>

  <TranistionButton/>

</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    background-color: #000000;
    /* Makes you feel like you are going insane... Mwah ha ha!!! */
    transition: background-color 60s cubic-bezier(0.25,1,0,-1.1);
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }
</style>
