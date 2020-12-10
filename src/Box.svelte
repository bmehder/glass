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
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.24);
  }
  @media screen and (max-width: 900px) {
    aside {
      width: 100%;
      margin: 1em;
      height: auto;
    }
  }
</style>
