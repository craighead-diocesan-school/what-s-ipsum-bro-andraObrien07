<script>
  import Footer from "$lib/Footer.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<main>
  <div class="container">
    <div class="subheading">
      <img src="poison.png" alt="poison" />
      <h2>Yar Pirate Ipsum</h2>
      <img src="poison.png" alt="poison" />
    </div>
  </div>
  <div class="pcontainer">
    <p>
      Maroon square-rigged rope's end spirits fathom tackle bilge rat careen
      cackle fruit splice the main brace. Arr to go on account bilge six
      pounders smartly yo-ho-ho yawl tack boatswain maroon. Barque hogshead
      coffer Buccaneer loot fire ship Shiver me timbers Blimey salmagundi reef.
    </p>

    <p>
      Draft scuttle rigging shrouds blow the man down belaying pin cog fluke
      strike colors killick. Gibbet case shot hulk main sheet landlubber or just
      lubber fathom Corsair coxswain reef Jolly Roger. Parrel jib man-of-war run
      a shot across the bow bounty maroon dead men tell no tales Cat o'nine
      tails ye swing the lead.
    </p>
  </div>
</main>

<!-- <div class="navBackround"> -->
<Nav color="#1A1D1A" />

<!-- </div> -->
<Footer />

<style>
  h2 {
    font-family: "hyper-scrypt";
    color: #d9edff;
    font-size: 300%;
  }

  /* .navBackround {
    background-image: url("flag.png");
  } */

  p {
    font-family: "basteleur";
    background-color: rgba(255, 255, 255, 0.65);
    margin: 4%;
    padding: 2%;
  }

  main {
    display: flex;
    align-items: bottom;
    justify-content: space-around;
    height: 500px;
    /* background-repeat: no-repeat; */
    background-image: url("wave.gif");
  }

  .pcontainer {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-repeat: no-repeat;
    height: 500px;
    background-image: url("ship.gif");
  }
  .subheading {
    display: flex;
    align-items: center;
    justify-content: space-around;
    height: 300px;
    background-image: url("flag.png");
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    height: 200px;
  }

  img {
    width: 100px;
  }
</style>
