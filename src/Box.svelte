<script>
  export let align = "center";
</script>

<aside style="text-align:{align};">
  <slot />
</aside>

<style>
  aside {
    width: 280px;
    /* height: 300px; */
    margin: 40px 0 0;
    padding: 2em;
    background: white;
    border-radius: 4px;
  }
  @media screen and (max-width: 600px) {
    aside {
      width: 100%;
      margin: 1em;
      height: auto;
    }
  }
</style>
