<script>
  export let color = "lavender";
</script>

<nav style="background: {color}">
  <div class="boxes">
    <a href="/">
      <img class="box" src="house.png" alt="House" />
    </a>

    <a href="/pirate">
      <img class="box" src="pirate.png" alt="Pirate" />
    </a>

    <a href="/cheese">
      <img class="box" src="cheese.png" alt="Cheese" />
    </a>

    <a href="/cupcake">
      <img class="box" src="cupcake.png" alt="Cupcake" />
    </a>

    <a href="/hipster">
      <img class="box" src="hipster.png" alt="Hipster" />
    </a>
  </div>
</nav>

<style>
  nav {
    background: lavender;

    font-family: "Patrick Hand", cursive;
    text-align: center;
    /* margin-top: 100px; */
    margin-bottom: 0;
  }

  .box {
    width: 75px;
    height: 75px;
    border-radius: 4%;
    padding: 25px;
    background: ivory;
    box-shadow: 15px 15px lightblue;
    transform: scale(1);
    transition: 0.25s;
  }

  .box:hover {
    transform: scale(1.1);
    transition: 0.25s;
  }

  .boxes {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
    justify-content: space-between;
    width: 400px;
  }
</style>
