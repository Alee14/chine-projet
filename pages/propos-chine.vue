<template>
  <div>
    <h1>À propos de la Chine</h1>
    <h2>Où est la Chine?</h2>
    <img src="~/assets/img/chine-petite.png" />
    <p>
      La Chine est sur le continent d'Asie très proche de la Russie, Mongolie,
      Indie, Khazakstan, Corée, Vietnam, Laos, Taiwan et Japon.
    </p>
    <img src="~/assets/img/map.jpg" height="40%" width="40%" />
    <h2>La capitale</h2>
    <p>La capitale de la Chine est Pékin (Aussi connu sous le nom Beijing).</p>
    <img src="~/assets/img/beijing.jpg" width="30%" height="30%" />
    <h2>Le chef de le pays</h2>
    <p>Xi Jinping</p>
    <img src="~/assets/img/Xi_Jinping_2019.jpg" width="10%" height="10%" />
    <h2>La population en Chine</h2>
    <p>Population est 1,439,323,776</p>
    <iframe :src="'/chart.html'" frameborder="0" height="605px" width="100%" />
    <h2>Les langues en Chine</h2>
    <p>Voici les langues chinoises surtout parlées:</p>
    <ul>
      <li>Mandarin [Langue officielle]</li>
      <li>Yue (Cantonais)</li>
      <li>Wu (Shanghaïen)</li>
      <li>Minbei (Fuzhou)</li>
    </ul>
    <h2>Religion en Chine</h2>
    <p>
      Les religions en Chine sont Religion traditionnelle chinoise (Taoïsme, des
      ancêtre, Culte des dieux), Bouddhisme, Chrétiens et Musulmans.
    </p>
    <h2>Le climat en Chine</h2>
    <img src="~/assets/img/climate.jpg" height="30%" width="30%" />
    <p>Température moyenne en Chine</p>
  </div>
</template>

<script>
export default {
  components: {},
}
</script>
