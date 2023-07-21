<script>
  import Timer from "./lib/Timer.svelte";
  import Counter from "./lib/Counter.svelte";
</script>

<div>
  <Timer />
</div>
<div>
  <Timer />
</div>
<div>
  <Timer />
</div>

<style>
  div {
    display: flex;
    justify-content: center;
    border: solid  rgb(12, 201, 235) 4px;
    border-radius: 50%;
    margin: 60px 250px;
    padding: 60px 60px;
  }
</style>
