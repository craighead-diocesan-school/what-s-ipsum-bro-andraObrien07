<script>
  import Footer from "$lib/Footer.svelte";
  import SNav from "$lib/SNav.svelte";
</script>

<SNav />

<main>
  <div class="subheading">
    <img class="subheader-image" src="flipflop.webp" alt="flipflops" />
    <h2>You Probably Haven't Heard of Hipster Ipsum</h2>
    <img class="subheader-image" src="flipflop.webp" alt="flipflops" />
  </div>

  <div class="bread">
    <img class="beard" src="bread.webp" alt="bread" />
  </div>
  <div class="pcontainer">
    <p>
      Fingerstache tofu pickled vibecession kitsch lyft blackbird spyplane vegan
      craft beer keytar banh mi thundercats. Hashtag heirloom vape scenester
      paleo hexagon. Blackbird spyplane pok pok DIY heirloom scenester food
      truck kale chips pabst, bitters raw denim artisan waistcoat seitan
      freegan.
    </p>

    <p>
      Put a bird on it vibecession fashion axe YOLO asymmetrical. VHS photo
      booth listicle fam truffaut subway tile yr cred chicharrones semiotics
      biodiesel green juice microdosing whatever. Truffaut praxis PBR and B
      tattooed street art. Prism jean shorts pickled vegan. Vegan praxis cronut
      kitsch pop-up. Letterpress street art mlkshk marxism.
    </p>
    <div />
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
    /* width: 100px; */
    background-image: url("grasss.webp");
  }

  .pcontainer {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-repeat: no-repeat;
    height: 300px;
    /* background-image: url("bread.webp"); */
    /* background-position: left; */
  }

  .subheader-image {
    width: 100px;
  }

  .bread {
    width: 100%;
    display: flex;
    justify-content: center;
  }

  .beard {
    width: 500px;
  }
</style>
