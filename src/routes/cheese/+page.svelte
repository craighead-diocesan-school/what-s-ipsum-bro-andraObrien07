<script>
  import Footer from "$lib/Footer.svelte";
  import SNav from "$lib/SNav.svelte";
</script>

<SNav color="rgb(250, 221, 106)" />

<main>
  <div class="subheading">
    <img src="cheeseicon.png" alt="cheese" />
    <h2>Pee-YOO Cheese Ipsum</h2>
    <img src="cheeseicon.png" alt="cheese" />
  </div>
  <div class="pcontainer">
    <div class="catcher">
      <p>
        Cheesy grin parmesan taleggio. Brie boursin pecorino cheesy feet
        taleggio hard cheese roquefort when the cheese comes out everybody's
        happy. St. agur blue cheese port-salut bocconcini cheesecake rubber
        cheese mozzarella stilton cheese strings. Bocconcini.
      </p>

      <p>
        Fromage the big cheese camembert de normandie. Cut the cheese gouda brie
        the big cheese when the cheese comes out everybody's happy squirty
        cheese cut the cheese gouda. Boursin cottage cheese cheeseburger
        camembert de normandie cheese slices goat port-salut danish fontina.
        Emmental caerphilly cream cheese mozzarella camembert de normandie
        cheesy feet.
      </p>
    </div>
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
    background-color: rgb(250, 221, 106);
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
    height: 500px;
    background-image: url("mouse.gif.webp");
    background-position: left;
  }
  .pcontainer:hover {
    background-position: right;
    transition: 5s;
  }

  h2 {
    font-family: "hyper-scrypt";
    color: #f9af40;
    font-size: 300%;
  }
  .catcher {
    background-image: url("cheeseicon.png");
    background-position: right;
    background-repeat: no-repeat;
  }
  main {
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url("disapearingcheese.gif");
    /* background-size: cover; */
    height: 1200px;
  }
</style>
