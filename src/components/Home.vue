<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-row>
          <v-col cols="12" md="6" class="pt-0">
            <v-row>
              <v-col cols="12" class="mb-0 pb-0">
                <v-img
                  src="../assets/drawing.png"
                  class="my-3"
                  contain
                  max-height="400"
                  alt="Late night computer user"
                />
              </v-col>
              <v-col class="mt-0 pt-0">
                <figcaption>Image: John Lee</figcaption>
              </v-col>
            </v-row>
          </v-col>
          <v-col cols="12" md="6" class="pt-6">
            <v-card>
              <v-card-title><h2>About Me</h2></v-card-title>
              <v-card-content>
                <p>
                  Hi!  My name is Clayton Stacy and I'm a web developer, dad, and coffee addict
                  living in the Midwest. I have worked in the defense industry for nearly 20 years,
                  but a couple of years ago I began to feel unsatisfied with the path my career
                  had taken. I was unhappy at work and knew I needed to make a change.  When
                  the opportunity to learn basic web development on the job presented itself, I
                  jumped at it.  Almost two years on, and I’m still learning; finishing a degree,
                  working full time, and taking care of a family.  It hasn’t been easy, but
                  hopefully I’m showing my boys that even if it takes you a while to figure out
                  what you want to be when you grow up, you are never too old to achieve it.
                </p>
              </v-card-content>
            </v-card>
          </v-col>
        </v-row>
        <br />
        <h2>API Presentations</h2>
        <v-row>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <video width="320" height="240" controls>
              <source src="../assets/slides/stacy-1.2-REST.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <video width="320" height="240" controls>
              <source src="../assets/slides/stacy-2.2-RESTful APIs.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <video width="320" height="240" controls>
              <source src="../assets/slides/stacy-3.3-SOAP.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <video width="320" height="240" controls>
              <source src="../assets/slides/stacy-3.4-JSON.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <video width="320" height="240" controls>
              <source src="../assets/slides/stacy-6.2-hypermedia-design-6-7-2020.mp4"
              type="video/mp4">
              Your browser does not support the video tag.
            </video>
          </v-card>
          </v-col>
        </v-row>
        <br />
        <h2>Projects</h2>
        <v-row>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <v-card-title>GPA Calculator App</v-card-title>
              <v-card-content>
                <a href="https://claytonstacy.github.io/gpa-calculator-app/session/sign-in">
                  <img src="../assets/calculator-thumb.png" alt="website-thumb" />
                </a>
              </v-card-content>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <v-card-title>Composer App</v-card-title>
              <v-card-content>
                <a href="https://claytonstacy.github.io/enterprise-composer-app/">
                  <img src="../assets/composer-thumb.png" alt="website-thumb" />
                </a>
              </v-card-content>
          </v-card>
        </v-col>
        <v-col cols="12" sm="6" md="4">
          <v-card>
            <v-card-title>NodeBucket</v-card-title>
            <v-card-content>
              <a href="https://stacy-nodebucket.herokuapp.com/#/">
                <img src="../assets/nodebucket-thumb.png" alt="website-thumb" />
              </a>
            </v-card-content>
        </v-card>
        </v-col>
          <v-col cols="12" sm="6" md="4">
            <v-card>
              <v-card-title>BCRS</v-card-title>
              <v-card-content>
                <a href="https://group2-bcrs.herokuapp.com/#/">
                  <img src="../assets/bcrs-thumb.png" alt="website-thumb" />
                </a>
              </v-card-content>
          </v-card>
        </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld',

  data: () => ({
  }),
};
</script>
