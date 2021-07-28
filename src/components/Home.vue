<template
  ><div>
    <v-row class="d-flex justify-center"
      ><v-col cols="12" md="10" lg="8">
        <v-card class=" mt-6 mb-6 ">
          <v-card outlined>
            <v-card-title class="text-h2">
              Hi! I'm Kabilan Balasubramani
            </v-card-title>
            <v-card-text class="text-subtitle-1">
              I'm an undergraduate student studying computer science who's
              impassioned by consumer facing technology. Feel free to reach out!
              Check out my resume if you want a boiled down version of my
              experience :)
            </v-card-text>
            <v-card-actions>
              <mdb-btn
                target="_blank"
                href="https://www.linkedin.com/in/kabilan-balasubramani-6146131b2/"
                tag="a"
                size="lg"
                floating
                class="btn-li rounded-circle transparent ml-1"
                icon="linkedin-in"
                fab
              ></mdb-btn>
              <mdb-btn
                target="_blank"
                href="https://github.com/Kabi22"
                tag="a"
                size="lg"
                floating
                class="btn-git rounded-circle transparent"
                icon="github"
                fab
              ></mdb-btn>
              <mdb-btn
                target="_blank"
                href="mailto:kabi.bala22@gmail.com"
                tag="a"
                size="lg"
                floating
                class="btn-email rounded-circle transparent "
                icon="envelope"
              ></mdb-btn>
              <mdb-btn
                target="_blank"
                href="Kabilan Balasubramani Resume.pdf"
                tag="a"
                size="lg"
                floating
                class=" rounded-circle transparent "
                icon="file"
              ></mdb-btn>
            </v-card-actions>
          </v-card>
        </v-card> </v-col
    ></v-row>

    <Timeline />
  </div>
</template>

<script>
import Timeline from "./Timeline.vue"
import { mdbBtn } from "mdbvue"

export default {
  name: "Home",
  components: {
    Timeline,
    mdbBtn,
  },
}
</script>

<style></style>
