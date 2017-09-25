<template>
  <div class="homepage">
    <div class="container has-text-centered">
      <img src="../assets/img/helloproclub-logo-white.svg">
      <div style="padding: 32px"></div>
      <h1 class="title">
        Open Recruitment
      </h1>
      <h2 class="subtitle">
        Coming Soon!
      </h2>
    </div>
    <div style="padding: 128px"></div>
    <div class="container is-fluid">
      <b-tabs v-model="tabs.active" type="is-boxed" expanded>
        <b-tab-item label="Ikhtisar">
          <div style="color: #222; background-color: #fff; padding: 32px 6px">
            <div class="container is-fluid">
              <div class="tile is-ancestor">
                <div class="tile is-parent">
                  <div class="tile is-child box notification is-white">
                    <p class="title" style="color: #444">Apa itu Proclub?</p>
                    <p style="margin-bottom: 16px; text-align: justify">
                      Proclub adalah komunitas di bawah naungan Fakultas
                      Informatika, Universitas Telkom yang menjadi inkubator
                      bagi mahasiswa Universitas Telkom dengan ketertarikan
                      tinggi terhadap perkembangan teknologi dan kompetisi ICT.
                    </p>
                    <p style="margin-bottom: 16px; text-align: justify">
                      Selama satu dekade ini kami dkenal oleh kalangan umum
                      sebagai komunitas pemrograman saja. Bahkan lebih dari
                      itu, selain Programmer kami memiliki keanggotaan yang
                      dibagi dari keahlian seperti Business Analyst dan Designer
                      UI/UX.
                    </p>
                    <p style="margin-bottom: 16px; text-align: justify">
                      Proclub Teknofest 2017 akan segera hadir di bulan ini.
                      Karena kami percaya "Collaboration Makes a Great Product".
                    </p>
                  </div>
                </div>
                <div class="tile is-4 is-vertical is-parent">
                  <div class="tile is-child box notification is-white">
                    <p class="title" style="color: #444">Programmer</p>
                    <p style="text-align: justify">
                      Logika dan kode pemrograman adalah kesehariannya.
                    </p>
                  </div>
                  <div class="tile is-child box notification is-white">
                    <p class="title" style="color: #444">Designer</p>
                    <p style="text-align: justify">
                      Warna, bentuk, dan posisi adalah kesehariannya.
                    </p>
                  </div>
                  <div class="tile is-child box notification is-white">
                    <p class="title" style="color: #444">Business Analyst</p>
                    <p style="text-align: justify">
                      Uang dan strategi bisnis adalah kesehariannya.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </b-tab-item>
        <b-tab-item label="Programmer">
          <section class="hero is-white is-medium">
            <div class="hero-body">
              <div class="container has-text-centered">
                <h1 class="title" style="color: #666">
                  Programmer
                </h1>
                <h2 class="subtitle" style="color: #666">
                  We're working on this!
                </h2>
              </div>
            </div>
          </section>
        </b-tab-item>
        <b-tab-item label="Designer">
          <section class="hero is-white is-medium">
            <div class="hero-body">
              <div class="container has-text-centered">
                <h1 class="title" style="color: #666">
                  Designer
                </h1>
                <h2 class="subtitle" style="color: #666">
                  We're working on this!
                </h2>
              </div>
            </div>
          </section>
        </b-tab-item>
        <b-tab-item label="Business Analyst">
          <section class="hero is-white is-medium">
            <div class="hero-body">
              <div class="container has-text-centered">
                <h1 class="title" style="color: #666">
                  Business Analyst
                </h1>
                <h2 class="subtitle" style="color: #666">
                  We're working on this!
                </h2>
              </div>
            </div>
          </section>
        </b-tab-item>
      </b-tabs>
    </div>
  </div>
</template>

<script>
export default {
  name: 'homepage',
  data () {
    return {
      title: 'Hello Proclub',
      tabs: {
        active: 0
      }
    }
  },
  head: {
    title: {
      inner: 'Hello',
      separator: '|',
      complement: 'Proclub'
    }
  }
}
</script>

<style scoped>
img {
  height: 200px;
}
</style>
