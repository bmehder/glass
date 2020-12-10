<script>
  import Flex from "./Flex.svelte";
  import Grid from "./Grid.svelte";
  import Section from "./Section.svelte";
  import Nav from "./Nav.svelte";
  import Hero from "./Hero.svelte";
  import Box from "./Box.svelte";
  import Glass from "./Glass.svelte";
  import Button from "./Button.svelte";
  import Card from "./Card.svelte";
  import Blockquote from "./Blockquote.svelte";
  import Footer from "./Footer.svelte";
  import Spacer from "./Spacer.svelte";
</script>

<Nav />

<div class="circle" />

<header>
  <Glass>Break Glass!</Glass>
</header>

<Section boxed padding="80px 0">
  <Card align="left">
    <h3>Section Heading</h3>
    <Grid columns="1fr 1fr" gap="2em" padding="1em">
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Odit,
        doloremque provident facilis, nam harum ratione aliquid sapiente ullam
        illum animi rerum cupiditate voluptates assumenda debitis, vitae
        veritatis commodi aliquam vel qui quis. Lorem ipsum dolor, sit amet
        consectetur adipisicing elit.
      </p>
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Odit,
        doloremque provident facilis, nam harum ratione aliquid sapiente ullam
        illum animi rerum cupiditate voluptates assumenda debitis, vitae
        veritatis commodi aliquam vel qui quis. Lorem ipsum dolor, sit amet
        consectetur adipisicing elit.
      </p>
    </Grid>
    <Blockquote shadow>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione aperiam
      quibusdam quod accusantium optio accusamus magnam?
    </Blockquote>
    <Grid columns="1fr 1fr" gap="2em" padding="1em">
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Odit,
        doloremque provident facilis, nam harum ratione aliquid sapiente ullam
        illum animi rerum cupiditate voluptates assumenda debitis, vitae
        veritatis commodi aliquam vel qui quis. Lorem ipsum dolor, sit amet
        consectetur adipisicing elit.
      </p>
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Odit,
        doloremque provident facilis, nam harum ratione aliquid sapiente ullam
        illum animi rerum cupiditate voluptates assumenda debitis, vitae
        veritatis commodi aliquam vel qui quis. Lorem ipsum dolor, sit amet
        consectetur adipisicing elit.
      </p>
    </Grid>
  </Card>
  <Flex justify="space-between" align="center">
    <Box>
      <Flex direction="column" justify="space-between" align="center">
        <p><i class="fas fa-5x fa-code" /></p>
        <Spacer height="1em" />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut nihil,
          rem aut expedita totam explicabo nobis quaerat soluta ad
          necessitatibus ab rerum libero perspiciatis, natus consequuntur!
        </p>
        <Button shadow>Make My Day</Button>
      </Flex>
    </Box>
    <Box>
      <Flex direction="column" justify="space-between" align="center">
        <p><i class="fab fa-5x fa-css3-alt" /></p>
        <Spacer height="1em" />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut nihil,
          rem aut expedita totam explicabo nobis quaerat soluta ad
          necessitatibus ab rerum libero perspiciatis, natus consequuntur!
        </p>
        <Button shadow>Make My Day</Button>
      </Flex>
    </Box>
    <Box>
      <Flex direction="column" justify="space-between" align="center">
        <p><i class="fab fa-5x fa-js-square" /></p>
        <Spacer height="1em" />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut nihil,
          rem aut expedita totam explicabo nobis quaerat soluta ad
          necessitatibus ab rerum libero perspiciatis, natus consequuntur!
        </p>
        <Button shadow>Make My Day</Button>
      </Flex>
    </Box>
  </Flex>
</Section>

<Hero background="https://source.unsplash.com/random/?1" height="400px">
  <Glass color="gold">A thing here.</Glass>
  <Button shadow>Make My Day</Button>
</Hero>

<Section margin="20px 0" padding="40px 0" />

<Footer background="#242424" color="#d1d1d1">
  <Flex justify="space-between">
    <p>©2021 Tom Foolery. All rights reserved.</p>
    <p>Made with the SvelteLana Component Library</p>
  </Flex>
</Footer>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;900&display=swap");
  :global(*) {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  :global(body) {
    padding: 0;
    background: radial-gradient(black 15%, transparent 16%) 0 0,
      radial-gradient(black 15%, transparent 16%) 8px 8px,
      radial-gradient(rgba(255, 255, 255, 0.1) 15%, transparent 20%) 0 1px,
      radial-gradient(rgba(255, 255, 255, 0.1) 15%, transparent 20%) 8px 9px;
    background-color: #282828;
    background-size: 16px 16px;
    /* background: #121212; */
    font-family: "Poppins", sans-serif;
  }
  div.circle {
    position: absolute;
    top: 110px;
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
  i {
    color: #121212;
  }
</style>
