<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="d-flex justify-center pb-4">
        <img
          src="~/assets/app_logo.png"
          alt="Application logo"
          width="120"
          height="120"
        />
      </div>
      <v-card>
        <v-card-title class="headline">
          Welcome to the website of project Chess Exercises Organizer Android.
        </v-card-title>
        <v-card-text>
          <p>
            Chess Exercises Organizer is an Android application that let you
            train yourself in chess by using positions taken from chess PGN
            files.
          </p>

          <p>Its main features are :</p>
          <ul>
            <li>the use of Stockfish 11 for the computer play,</li>
            <li>the possibility to use some integrated PGN files,</li>
            <li>the possibility to create your own PGN files,</li>
            <li>
              the possibility to download|upload PGN files from/to your Google
              Drive account.
            </li>
          </ul>

          <p></p>
          <p>
            Custom PGN file can handle several exercises if you want : they will
            be handled by the program so that you can choose the exercise.
          </p>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  components: {},
}
</script>
