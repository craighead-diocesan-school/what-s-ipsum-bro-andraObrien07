<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<Header />

<Nav />
<main>
  <div class="columns">
    <h2>Pee-YOO Cheese Ipsum</h2>
    <div class="text">
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
  .columns {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    background: lavender;
    padding: 5rem 10rem;
  }
</style>
