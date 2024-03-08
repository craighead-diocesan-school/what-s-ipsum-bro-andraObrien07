<script>
  import Footer from "$lib/Footer.svelte";
  import SNav from "$lib/SNav.svelte";
</script>

<SNav />
<main>
  <div class="subheading">
    <img class="subCupcake" src="/cupcakes.png" alt="cupcakes" />
    <h2>Yum Cupcake Ipsum</h2>
    <img class="subCupcake" src="/cupcakes.png" alt="cupcakes" />
  </div>
  <div class="pcontainer">
    <!-- <img class="landingCupcake" src="Kcupcake.png" alt="cupcake" /> -->
    <p>
      Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu.
      Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart
      cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream
      sugar plum jujubes dragée topping tiramisu croissant chocolate. Jujubes
      tiramisu gingerbread cake donut chocolate bar tart marzipan pastry.
    </p>
    <p>
      Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake
      chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot
      cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer
      chocolate bar sweet roll macaroon soufflé powder sugar plum tart.
    </p>
  </div>
</main>
<Footer />

<style>
  .subheading {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-size: cover;
    height: 150px;
    background-color: #fd83ff;
  }
  /* .landingCupcake {
    width: 700px;
  }
  .landingCupcake:hover {
    background-position: bottom;
    transition: 4s; */
  /* } */
  main {
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url("/equipment.webp");
    height: 900px;
    /* background-image: url("Kcupcake.png");
    background-position: bottom; */
  }
  p {
    font-family: "basteleur";
    background-color: rgba(255, 255, 255, 0.65);
    margin: 4%;
    padding: 2%;
  }

  .pcontainer {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-repeat: no-repeat;
    height: 300px;
    background-image: url("/Kcupcake.png");
    background-position: bottom;
  }
</style>
