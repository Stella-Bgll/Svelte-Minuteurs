<script>
  let seconds = 0;
  const incrementSeconds = () => {
    seconds++;
  };
  setInterval(incrementSeconds, 1000);

  const reset = () => {
    seconds = 0;
  };
</script>

<div>
  <label for="">Secondes écoulées</label>
  <p>{seconds}</p>
  <button on:click={reset}>Remise à zéro</button>
</div>

<style>
  button {
   color: blue;
   background: rgb(211, 13, 145);
 }
</style>
