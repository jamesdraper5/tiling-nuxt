<template>
  <div>
    <div class="hero">
      <div class="hero-content">
        <h1 class="display-4">
          Quality Tiling in West Cork
        </h1>
        <div class="row">
          <div class="col-md-6 offset-md-3">
            <p class="lead">
              West Cork Tiling offers a professional tiling service at an affordable price. With over 10 years of experience in the tiling industry and 20 years of experience in the building industry as a whole, we can offer a tailored solution to any tiling project.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- <b-img src="wetroom.jpg" fluid alt="Tiling in Skibbereen" /> -->

    <div class="container">
      <div>
        <hr class="my-4">
        <p>Our skilled tilers deliver a quality service to suit any budget and can also offer advice on the design and layout of your project. We can also prepare the area to be tiled, for example removing skirting boards before the area is tiled. No job is too big or too small, so why not take a look at some of our previous work and call us for a quote, or fill out our enquiries form and we will be in touch to discuss your requirements.</p>
        <b-btn variant="outline-info" href="#work">
          View our work
        </b-btn>
        <b-btn variant="info" href="tel:0863353276">
          Make an enquiry
        </b-btn>
      </div>

      <div class="row">
        <div class="col-sm">
          <p>We offer a wide range of tiling jobs in the West Cork area including:</p>
          <ul>
            <li>Bathroom tiling</li>
            <li>Kitchen tiling</li>
            <li>Wall tiling</li>
            <li>Floor tiling</li>
            <li>Backsplashes</li>
            <li>Wetrooms</li>
          </ul>
        </div>
        <div class="col-sm">
          <p>We have extensive experience using the following materials:</p>
          <ul>
            <li>Ceramic tiles</li>
            <li>Porcelain tiles</li>
            <li>Natural stone tiles</li>
            <li>Slate tiles</li>
            <li>Terracotta tiles</li>
            <li>Brick effect tiles</li>
          </ul>
        </div>
      </div>

      <hr class="my-5">

      <section id="work">
        <h2 class="mb-3">
          Our Work
        </h2>

        <div id="gallery" class="gallery">
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/mosaic-tiling.jpg" alt="test" class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/bathroom-tiling-cork.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/bath.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/cork-bathroom-tiling-1.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/cork-bathroom-tiling-3.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/bathroom-tiling-cork-5.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/cork-bathroom-tiling-2.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/bathroom-tiling-cork-2.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/floor-tiling.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/bathroom-tiling-cork-3.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/bathroom-tiling-cork-4.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/kitchen-tiling.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/kitchen-tiling-2.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/floor-tiling-2.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/mosaic-tiling-2.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/mosaic-tiling-cork.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/tiling-cork.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/tiling-shower.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/kitchen-tiling-4.jpg" alt="..." class="img-fluid">
          </div>
          <div class="mb-3 pics">
            <img v-img:gallery src="tiling-work/kitchen-tiling-3.jpg" alt="..." class="img-fluid">
          </div>
        </div>
      </section>

      <hr class="my-5">

      <section id="about">
        <h2 class="mb-3">
          About West Cork Tiling
        </h2>

        <div class="row">
          <div class="col-sm">
            <p>West Cork Tiling is a website promoting the services of Bob Draper, a professional tiler based near Skibbereen in County Cork. Bob has twenty years experience in the tiling industry and prides himself on his high quality work and attention to detail. Having worked in the construction industry for almost forty years, Bob has a wealth of experience and expertise in tiling and general construction subjects, and is always willing to offer advice on your tiling project.</p>

            <p>Tiling services are available anywhere in the West Cork area, from Dunmanway to Clonakilty and Schull to Bandon.</p>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
</script>

<style>
h1,
h2 {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-weight: 300;
  color: #35495e;
  letter-spacing: 1px;
}

/*
h1,
h2 {
  font-family: 'Comfortaa', cursive;

  font-family: 'Rubik', sans-serif;
  font-family: 'Nanum Gothic', sans-serif;
  font-family: 'Abril Fatface', cursive;
  font-family: 'Questrial', sans-serif;
}
*/

.hero {
  background-image: url('/wetroom3.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hero-content {
  width: 100%;
  justify-content: center;
  align-items: center;
  flex-direction: inherit;
  flex-flow: column;
  display: flex;
  color: #fff;
}

.hero-content h1 {
  font-family: 'Playfair Display', serif;
  letter-spacing: 2px;
  color: #fff;
  text-shadow: 1px 2px 5px #000;
}

.hero-content p {
  background: #0003;
  margin-top: 20px;
  padding: 10px 20px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.gallery {
  column-count: 3;
  column-width: 33%;
}

@media (max-width: 450px) {
  .gallery {
    column-count: 1;
    column-width: 100%;
  }
}
</style>
