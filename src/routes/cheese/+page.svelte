<script>
  import Footer from "$lib/Footer.svelte";
  import SNav from "$lib/SNav.svelte";
</script>

<SNav color="rgb(250, 221, 106)" />

<main>
  <div class="subheading">
    <img src="/cheeseicon.png" alt="cheese" />
    <h2>Pee-YOO Cheese Ipsum</h2>
    <img src="/cheeseicon.png" alt="cheese" />
  </div>

  <!-- <div class="prints">
    <img src="/prints.png" alt="rat prints" />
  </div> -->
  <div class="pcontainer">
    <!-- <div class="prints">
      <img src="/prints.png" alt="rat prints" />
    </div> -->

    <div class=" cheesepic">
      <img src="/cheeseicon.png" alt="cheese" />
    </div>

    <div class="ratpic">
      <img src="/prints.png" alt="rat prints" />
      <img src="/rat.png" alt="rat" />
    </div>

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
    background-image: url("/cheeseholes.jpeg");
    background-color: rgb(250, 221, 106);
  }

  p {
    font-family: "Patrick Hand", cursive;
    width: 30%;
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

    background-color: rgb(250, 221, 106);
    background-position: left;
  }
  .pcontainer:hover {
    background-position: right;
    transition: 5s;
  }
  /* .prints {
    border-image-width: 5%;
  } */

  .cheesepic {
    right: 10%;
    position: absolute;
    /* transition: 4s; */
  }

  .ratpic {
    position: left;
    position: absolute;
    right: 50%;
    transition: 4s;
  }
  main:hover .ratpic {
    right: 5%;
    transition: 4s;
  }

  h2 {
    font-family: "Patrick Hand", cursive;
    width: 30%;
    color: #f9f5f1;
    font-size: 300%;
  }
  .catcher {
    /* background-image: url("/rat.png"); */
    /* background-image: url("/cheeseicon.png"); */
    background-position: right;
    background-repeat: no-repeat;
  }
  main {
    /* display: flex; */
    background-repeat: no-repeat;
    background-size: cover;
    height: 1200px;
  }
</style>
