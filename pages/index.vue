<template>
  <section class="hero is-info is-fullheight">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <div class="navbar-item">
              <img src="~/assets/panteon-logo.png" alt="Logo">
            </div>
          </div>
          <div id="navbarMenu" class="navbar-menu">
            <div class="navbar-end">
              <span class="navbar-item">
                <a class="button is-white is-outlined" target="blank" :href="phone">
                  <span class="icon">
                    <b-icon icon="phone" />
                  </span>
                  <span>Apeleazã acum</span>
                </a>
              </span>
              <span class="navbar-item">
                <a class="button is-white is-outlined" target="blank" :href="directions">
                  <span class="icon">
                    <b-icon icon="map" />
                  </span>
                  <span>Cum ajungem</span>
                </a>
              </span>
            </div>
          </div>
        </div>
      </nav>
    </div>

    <div>
      <div class="container has-text-centered">
        <div class="column is-8 is-offset-2">
          <h1 class="title">
            Pal melaminat · Debitare Pal · Cantuire · Accesorii
          </h1>

          <h2 class="subtitle">
            MDF | PFL | Blaturi de bucatarie

            <br>
            <hr>

            Prețuri negociabile.
            <br>
            <hr>

            Consiliere de specialitate  · Legături directe cu distribuitori de top
          </h2>
        </div>

        <div class="column is-8 is-offset-2 pan-map">
          <div>
            <h3 class="title is-5 has-text-left has-text-centered-desktop">
              Adresa:
            </h3>
            <p>
              Bulevardul Regele Mihai I (B-dul Bucuresti) 45, Baia Mare
              , sub restaurant "Crenguta"
            </p>

            <div>
              <a class="button is-white is-outlined" target="blank" :href="directions">
                <span class="icon">
                  <b-icon icon="map-marker" />
                </span>
                <span> Panteon Aspect SRL</span>
              </a>
            </div>
          </div>

          <div class="pan-map-map">
            <img src="~/assets/panteon_street.png" alt="hartã">
          </div>

          <div class="pan-map-map">
            <img src="~/assets/panteon_map.png" alt="hartã">
          </div>
        </div>

        <div class="pan-materials">
          <!--
          <card
            :title="materials.accesorii_mobilier.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.accesorii_mobilier.title"
            :image="materials.accesorii_mobilier.image"
          /> -->
        <!-- <card
            :title="materials.accesorii_sarpante.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.accesorii_sarpante.title"
            :image="materials.accesorii_sarpante.image"
          /> -->
        <!-- <card :title="materials.blaturi_de_bucatarie.title" class="is-one-quarter-desktop is-full-mobile" :image-alt="materials.blaturi_de_bucatarie.title" :image="materials.blaturi_de_bucatarie.image" /> -->
        <!-- <card
            :title="materials.bca.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.bca.title"
            :image="materials.bca.image"
          /> -->
        <!-- <card
            :title="materials.boltari.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.boltari.title"
            :image="materials.boltari.image"
          /> -->
        </div>

        <!-- <div class="columns pan-materials"> -->
        <!-- <card
            :title="materials.ciment.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.ciment.title"
            :image="materials.ciment.image"
          />
          <card
            :title="materials.hidroizolatii.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.hidroizolatii.title"
            :image="materials.hidroizolatii.image"
          />
          <card
            :title="materials.mortar.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.mortar.title"
            :image="materials.mortar.image"
          /> -->
        <!-- <card
            :title="materials.pal.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.pal.title"
            :image="materials.pal.image"
          />
        </div> -->

        <!-- <div class="columns pan-materials"> -->
        <!-- <card
            :title="materials.panouri_bordurate.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.panouri_bordurate.title"
            :image="materials.panouri_bordurate.image"
          /> -->
        <!-- <card
            :title="materials.plasa_gard.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.plasa_gard.title"
            :image="materials.plasa_gard.image"
          /> -->
        <!-- <card
            :title="materials.plasa_sudata.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.plasa_sudata.title"
            :image="materials.plasa_sudata.image"
          />
          <card
            :title="materials.rigips.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.rigips.title"
            :image="materials.rigips.image"
          /> -->
        <!-- </div> -->

        <!-- <div class="columns pan-materials"> -->
        <!-- <card
            :title="materials.samota.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.samota.title"
            :image="materials.samota.image"
          />
          <card
            :title="materials.spalieri.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.spalieri.title"
            :image="materials.spalieri.image"
          /> -->
        <!-- <card
            :title="materials.termoizolatii.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.termoizolatii.title"
            :image="materials.termoizolatii.image"
          />
          <card
            :title="materials.var.title"
            class="is-one-quarter-desktop is-full-mobile"
            :image-alt="materials.var.title"
            :image="materials.var.image"
          /> -->
        <!-- </div> -->
        <!-- </div> -->
        <!-- </div> -->

        <section class="section pan-description">
          <div class="container column is-8 is-offset-2 has-text-centered">
            <h3 class="subtitle">
              Panteon Aspect SRL, Baia Mare
            </h3>

            <p>
              O afacere localã mică.
              <br>
              <br>
              De peste 20 de ani ajutăm maramureșenii să construiască.
              <br>
              <br>
              Prețuri mici și negociabile.
              <br>
            </p>

            <hr>

            <br>
            Este un depozit de materiale construcţii in Baia Mare ce ofera:
            <br>
            Accesorii mobilier, pal melaminat și multe altele.
            <br>
            <hr>
            <br>
            Exista și posibilitate de colaborare pentru manufactura de produse.
          </div>
        </section>

        <footer class="footer has-text-white">
          <div class="mb-100 has-text-centered content columns">
            <div class="column is-3 is-offset-2 is-size-3 footer-link">
              <b-icon icon="phone" /> <a target="blank" :href="phone">0722 682 913</a>
            </div>
            <div class="column is-4 is-size-3 footer-link">
              <b-icon icon="email" /> <a target="blank" :href="email">panteonaspect@gmail.com</a>
            </div>
          </div>

          <div class="content column is-4 is-offset-4">
            <table itemprop="openingHours">
              <tbody>
                <tr>
                  <th class="has-text-white">
                    luni:
                  </th>
                  <td>
                    <span>08:00–17:00</span>
                  </td>
                </tr>
                <tr>
                  <th class="has-text-white">
                    marti:
                  </th>
                  <td>
                    <span>08:00–17:00</span>
                  </td>
                </tr>
                <tr>
                  <th class="has-text-white">
                    miercuri:
                  </th>
                  <td>
                    <span>08:00–17:00</span>
                  </td>
                </tr>
                <tr>
                  <th class="has-text-white">
                    joi:
                  </th>
                  <td>
                    <span>08:00–17:00</span>
                  </td>
                </tr>
                <tr>
                  <th class="has-text-white">
                    vineri:
                  </th>
                  <td>
                    <span>08:00–17:00</span>
                  </td>
                </tr>
                <tr>
                  <th class="has-text-white">
                    sâmbata:
                  </th>
                  <td>
                    <span>08:00–12:00</span>
                  </td>
                </tr>
                <tr>
                  <th class="has-text-white">
                    duminica:
                  </th>
                  <td>
                    <span>Închis</span>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </footer>
      </div>
    </div>
  </section>
</template>

<script>
// import Card from '~/components/Card'

export default {
  components: {
    // Card
  },
  data () {
    return {
      phone: 'tel:+40-722-682-913',
      directions: 'https://www.google.com/maps/dir//b-dul%20bucuresti%20nr.%2045%20baia%20mare',
      map: 'https://maps.app.goo.gl/TgJ6oitA3xejHfTb9',
      email: 'mailto:panteonaspect@gmail.com',
      materials: {
        accesorii_mobilier: {
          title: 'Accesorii mobilier',
          image: 'material.accesorii_mobilier.jpg'
        },
        accesorii_sarpante: {
          title: 'Accesorii șarpante',
          image: 'material.accesorii_sarpante.jpg'
        },
        blaturi_de_bucatarie: {
          title: 'Blaturi de bucatarie',
          image: 'material.blaturi_de_bucatarie.jpg'
        },
        bca: {
          title: 'BCA',
          image: 'material.bca.jpg'
        },
        boltari: {
          title: 'Bolțari beton pentru zidărie, fundație',
          image: 'material.boltari.jpg'
        },
        ciment: {
          title: 'Ciment',
          image: 'material.ciment.jpg'
        },
        hidroizolatii: {
          title: 'Hidroizolații',
          image: 'material.hidroizolatii.jpg'
        },
        mortar: {
          title: 'Mortar',
          image: 'material.mortar.jpg'
        },
        pal: {
          title: 'Pal melaminat',
          image: 'material.pal.jpg'
        },
        panouri_bordurate: {
          title: 'Panouri bordurate',
          image: 'material.panouri_bordurate.jpg'
        },
        plasa_gard: {
          title: 'Plasă gard',
          image: 'material.plasa_gard.jpg'
        },
        plasa_sudata: {
          title: 'Plasă sudată',
          image: 'material.plasa_sudata.jpg'
        },
        rigips: {
          title: 'Rigips',
          image: 'material.rigips.jpg'
        },
        samota: {
          title: 'Șamotă, semișamotă',
          image: 'material.samota.jpg'
        },
        spalieri: {
          title: 'Spalieri',
          image: 'material.spalieri.jpg'
        },
        termoizolatii: {
          title: 'Termoizolații',
          image: 'material.termoizolatii.jpg'
        },
        var: {
          title: 'Var',
          image: 'material.var.jpg'
        }
      }
    }
  }
}
</script>

<style>
  a {
    color: #d3d3d3;
  }

  @media screen and (max-width: 1023px) {
    .navbar-menu {
      display: block !important;
      background: none !important;
    }
  }

  .navbar-item img {
    max-height: 4.75rem;
  }

  .pan-map {
    margin-top: 100px;
  }

  .pan-map a {
    margin-top: 20px;
  }

  .pan-map-map {
    margin-top: 50px;
  }

  .pan-materials {
    margin-top: 100px;
    /* RESPONSIVE W */
  }

  .pan-description {
    background-color: rgba(15, 11, 9, 0.6);
  }

  .footer {
    background-color: #0f0b09;
  }

  .footer>.footer-link {
    color: white;
  }

  .mb-100 {
    margin-bottom: 100px;
  }
</style>
