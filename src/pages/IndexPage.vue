<template>
  <q-page>
    <q-parallax
      :height="300"
      :speed="0.9"
      src="https://static.asianpaints.com/content/dam/asianpaintsbeautifulhomes/home-decor-advice/guides-and-how-tos/choosing-living-room-furniture/Title-living-room-interior-design.jpg"
    >
      <h1 class="text-white">Wow</h1>
    </q-parallax>

    <div class="row q-ma-sm justify-center items-center">
      <div class="col-xs-12 col-sm-6 col-md-4">
        <h4>Our Craftsmanship</h4>
        <p>
          At Yatzkan Woodworks, we take pride in our commitment to quality
          craftsmanship. Each piece is meticulously handcrafted using carefully
          selected, sustainably sourced wood. Our skilled artisans combine
          traditional woodworking techniques with modern precision to create
          furniture and decor that stands the test of time.
        </p>
      </div>
      <div class="col-xs-12 col-sm-6 col-md-4">
        <h4>Custom Creations</h4>
        <p>
          We understand that every space is unique, and your furniture should be
          too. Explore our range of customizable options to tailor your
          furniture to fit your style, size, and finish preferences. Whether
          you're envisioning a rustic farmhouse dining table or a sleek modern
          coffee table, we work closely with you to ensure your custom piece is
          a perfect reflection of your taste.
        </p>
      </div>
      <div class="col-xs-12 col-sm-6 col-md-4">
        <h4>Sustainable Practices</h4>
        <p>
          As stewards of the environment, we are committed to sustainable
          practices. Our wood is sourced from responsibly managed forests, and
          we strive to minimize waste in our production process. By choosing
          Yatzkan Woodworks, you're not just investing in beautiful furniture;
          you're contributing to a greener, more sustainable future.
        </p>
      </div>
      <div class="row justify-center items-center">
        <div class="col-xs-12 col-sm-6 col-md-4">
          <h4>Browse Our Collections</h4>
          <p>
            Explore our online gallery to discover a curated selection of our
            signature pieces. From elegant bedroom sets to charming home
            accents, each item is designed to add warmth and character to your
            home. We believe in the power of wood to tell a story, and our
            collections showcase the versatility and beauty of this natural
            material.
          </p>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-4">
          <h4>Client Satisfaction</h4>
          <p>
            Our clients are at the heart of everything we do. We pride ourselves
            on open communication, transparency, and a commitment to exceeding
            your expectations. Read what our satisfied customers have to say and
            join the growing community of individuals who have chosen Yatzkan
            Woodworks for their bespoke furniture needs.
          </p>
        </div>
      </div>
    </div>
    <q-img
      height="900px"
      src="https://images.pexels.com/photos/129731/pexels-photo-129731.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
    >
      <h2 class="text-white row justify-center">Our Work</h2>

      <div
        class="row justify-center q-pa-md"
        style="background: rgba(0, 0, 0, 0)"
      >
        <q-card class="q-ma-md" v-for="item in 9" :key="item">
          <q-item-section>
            <q-item style="width: 200px">
              <q-img
                src="https://www.therange.co.uk/media/0/4/1657274071_12_2234.jpg"
            /></q-item>
          </q-item-section>
        </q-card>
      </div>
    </q-img>
  </q-page>
</template>
<script setup lang="ts"></script>

<style scoped>
p {
  font-family: sans-serif;
  font-size: 20px;
  margin: auto;
  padding: 15px;
}
h4 {
  font-style: italic;
  font-weight: 700;
  font-family: serif;
  margin: 5px;
  padding-left: 10%;
}
</style>
