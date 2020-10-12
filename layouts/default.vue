<template>
  <v-app dark>
    <v-main>
      <v-container>
        <nuxt />
        <footer>
          <v-row align="center" justify="center">
            <v-col>
              <v-btn to="/">Accueil</v-btn>
              |
              <v-btn to="/propos-chine">À propos Chine</v-btn>
              |
              <v-btn to="/culture">Culture</v-btn>
              |
              <v-btn to="/a-propos">À propos</v-btn>
              <br />
              <br />
              <p>
                Propulsé par NuxtJS. Sous licence
                <a href="https://www.gnu.org/licenses/gpl-3.0.en.html"
                  >GNU General Public License 3.0</a
                >.
                <br />
                <a href="https://github.com/Alee14/chine-projet/">
                  La code source pour cette projet.</a
                >
              </p>
              <p>&copy; Droits d'Auteur 2020 Andrew Lee.</p>
            </v-col>
          </v-row>
        </footer>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data() {
    return {}
  },
}
</script>
