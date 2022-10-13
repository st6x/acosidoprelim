<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="red--text text--darken-4 top">Hello Im Maeko</h5>
          <h1 class="white--text">Maeko Acosido</h1>
          <p class="grey--text">
          I'm a 4th Year BSIT Student from La Consolacion College Bacolod<br />
          I enjoy taking complex problems and turning them into simple and beatiful designs, <br>
          I also love logic and structure coding and always strive for an efficient code, whether it be HTML, CSS or Java <br>
          <br>
          When I'm not coding or creating things in photoshop, you'll find me in cafes or in the gym
          </p>
          <v-btn tile color="#FFF"> about me </v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#FFF" x-large class="ml-3"
                    >palette  </v-icon>

                  <h3 class="white--text ml-3 mt-4">UI Design</h3>
                  <p class="grey--text ml-3 mt-6">
                    Constructing software or hardware <br>
                    interfaces that emphasize style<br>
           
                    <br>
                  </p>
                  <v-btn color="#FFF" dark text>
                    Read more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="" x-large class="ml-3" dark
                    >tab</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">HTML Programmer</h3>
                  <p class="grey--text ml-3 mt-6">
                    Developing websites using client server models <br>
                    typically uses HTML, CSS and JavaScript in the Client <br>
                     PHP, C#, Python and Node.
                  </p>
                  <v-btn color="" dark text>
                    Read more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#FFF" x-large class="ml-3"
                    >computer</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Vector Art</h3>
                  <p class="grey--text ml-3 mt-6">
                    Vector artwork is art that's made up of vector graphics.<br>
                    These graphics are points, lines, curves and <br>
                    shapes that are based on mathematical formulas. 
                  </p>
                  <v-btn color="#FFF" dark text>
                    Read more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="white--text">SAMPLE WORKS</h4>
          <p class="grey--text">These are some of my works</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#FFF" light> Preivew </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="3.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="2.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> Vector Art </v-btn
          ><br />

          <v-btn color="#FFF" dark text class="ml-n4">
            See more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> My Website </v-btn><br />

          <v-btn color="#FFF" dark text class="ml-n4">
            See more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="4.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="5.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> UI Design </v-btn
          ><br />

          <v-btn color="#FFF" dark text class="ml-n4">
            See more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Vector Portrait </v-btn><br />
          <v-btn color="#FFF" dark text class="ml-n4">
            See more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">
                    Hire me
                  </h1>
                  <br>
                  <p class="grey--text">
                  Let's talk about your website or project send me a message and I will be in touch with you.
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn tile color="#FFF" light class="mt-16">
                    Contact
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text>Home</v-btn>
              <v-btn text>Skills</v-btn>
              <v-btn text>Sample Works</v-btn>
              <v-btn text>Contacts</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 370px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #1dabce;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>