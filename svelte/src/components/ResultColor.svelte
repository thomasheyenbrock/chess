<script>
  export let color = "";
</script>

<style>
  .result {
    border-radius: 50%;
    border: 2px solid #424240;
    height: 16px;
    width: 16px;
  }

  .result.black {
    background-color: #000000;
  }
  .result.white {
    background-color: #ffffff;
  }
</style>

<span class={`result ${color}`} />
