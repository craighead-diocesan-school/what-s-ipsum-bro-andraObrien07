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
    <div class="cherrycup">
      <img src="cherrys.png" alt="cherrys" />
      <!-- </div>
    <div class="Kcupcake"> -->
      <img src="/Kcupcake.png" alt="Kcupcake" />
    </div>
  </div>
</main>
<Footer />

<style>
  .cherrycup {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
    transition: 3s;
  }

  .pcontainer:hover .cherrycup {
    justify-content: center;
    transition: 3s;
  }

  .subheading {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-size: cover;
    height: 150px;
    background-color: #fd83ff;
  }

  main {
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url("/equipment.webp");
    height: 900px;
  }

  h2 {
    font-family: "Lobster";
    font-size: 400%;
  }
  p {
    font-family: "Lobster";
    background-color: rgba(255, 255, 255, 0.65);
    margin: 4%;
    padding: 2%;
  }

  .pcontainer {
    display: flex;
    align-items: center;
    justify-content: space-around;
    height: 600px;
  }

  @media screen and (max-width: 1000px) {
    main {
      margin-right: 10px;
      margin-left: 10px;
    }
  }
</style>
