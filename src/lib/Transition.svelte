<script>

  function handleClick() {
    alert("You clicked me!")
  }

</script>

<button on:click={handleClick}>
  Hello!
</button>

<style>

	button {
    padding: 1em 2em;
    width: 150px;
		background-color: #aaa;
		border: 2px soild #000000;
		color: #000000;
		font-size: inherit;
    font-family: inherit;
		background-image: linear-gradient(45deg, #666666 50%, transparent 50%);
		background-position: 100%;
		background-size: 400%;
		transition: background .5s ease-out, color 1s ease-out;
		border-radius: 2em;
	}
	button:hover {
		background-position: 0;
		color: #ffffff;
	}

</style>