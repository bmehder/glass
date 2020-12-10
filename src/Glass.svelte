<script>
  export let color = "white";
</script>

<div style="color:{color};" class="glass">
  <slot />
</div>

<style>
  .glass {
    max-width: 600px;
    padding: 0 1em;
    height: 200px;
    margin: 0 auto;
    font-size: 4em;
    font-weight: bold;
    line-height: 200px;
    border-radius: 4px;
    box-shadow: 1px 1px 5px rgba(255, 255, 255, 0.8) inset,
      10px 10px 20px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(20px);
    text-align: center;
    text-shadow: 0 0 1px rgba(0, 0, 0, 0.8);
  }
  @media screen and (max-width: 600px) {
    .glass {
      font-size: 2em;
    }
  }
</style>
