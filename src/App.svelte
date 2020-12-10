<script>
  import Nav from "./Nav.svelte";
  import Flex from "./Flex.svelte";
  import Section from "./Section.svelte";
  import Hero from "./Hero.svelte";
  import Box from "./Box.svelte";
</script>

<Nav />

<div class="circle" />

<header>
  <section>Break Glass!</section>
</header>

<Section padding="40px 0">
  <Flex justify="space-around" align="center">
    <Box>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut nihil, rem
      aut expedita totam explicabo nobis quaerat soluta ad necessitatibus ab
      rerum libero perspiciatis, natus consequuntur!
    </Box>
    <Box>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut nihil, rem
      aut expedita totam explicabo nobis quaerat soluta ad necessitatibus ab
      rerum libero perspiciatis, natus consequuntur!
    </Box>
    <Box>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut nihil, rem
      aut expedita totam explicabo nobis quaerat soluta ad necessitatibus ab
      rerum libero perspiciatis, natus consequuntur!
    </Box>
  </Flex>
</Section>

<Hero background="https://source.unsplash.com/random/?1" height="400px">
  <section>A thing here.</section>
</Hero>

<Section margin="40px 0" padding="40px 0" />

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;900&display=swap");
  :global(*) {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  :global(body) {
    padding: 0;
    background: #121212;
    font-family: "Poppins", sans-serif;
  }
  div.circle {
    position: absolute;
    top: 100px;
    left: 35%;
    transform: translateX(-50%);
    width: 300px;
    height: 300px;
    background: #f06;
    border-radius: 50%;
  }
  header {
    width: 100%;
    padding: 50px;
    height: 300px;
    margin: auto;
    background: url("https://source.unsplash.com/random") no-repeat center
      center/cover;
  }
  section {
    width: 600px;
    height: 200px;
    margin: auto;
    font-size: 4em;
    font-weight: bold;
    line-height: 200px;
    border-radius: 4px;
    box-shadow: 1px 1px 5px rgba(255, 255, 255, 0.8) inset,
      10px 10px 20px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(20px);
    text-align: center;
    color: white;
    text-shadow: 0 0 1px rgba(0, 0, 0, 0.8);
  }
</style>
