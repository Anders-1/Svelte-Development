<script>
  let count = 0
  export let text

  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment}>
  {text}: {count}
</button>

<style>

  button {
    font-family: inherit;
    font-size: inherit;
    padding: 1em 2em;
    color: #000000;
    background-color: #bababa;
    border-radius: 2em;
    border: 2px solid #000000;
    width: 150px;
    font-variant-numeric: tabular-nums;
    transition: background-color 0.5s ease-out, color 0.5s ease-out; 
  }

  button:hover {
    background-color: #666666;
    color: #ffffff;
    transition: background-color 0.5s ease-out, color 0.5s ease-out; 
  }

</style>
