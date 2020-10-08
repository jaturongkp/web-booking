<template>
  <v-card>
    <v-sheet class=" pa-4 light-blue darken-4 lighten-2">
      <v-text-field
        v-model="search"
        label="Search "
        dark
        flat
        solo-inverted
        hide-details
        clearable
        clear-icon="mdi-close-circle-outline"
      />
      <v-row>
        <v-checkbox
          v-model="caseSensitive"
          class="ma-3"
          dark
          hide-details
          label="Vip Room"
        />
        <v-checkbox
          v-model="caseSensitive"
          class="ma-3"
          dark
          hide-details
          label="Sweet room"
        />
        <v-checkbox
          v-model="caseSensitive"
          class="ma-3"
          dark
          hide-details
          label="Party room"
        />
        <v-checkbox
          v-model="caseSensitive"
          class="ma-3"
          dark
          hide-details
          label="Luxury room"
        />
        <v-rating
          v-model="rating"
          background-color="orange lighten-5"
          color="orange"
          large
        />
      </v-row>
    </v-sheet>
    <v-card>
      <v-row>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://pix10.agoda.net/hotelImages/209/2092140/2092140_17031512040051555216.jpg?s=1024x768"
          >
            <v-card-title>Sweet room</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://images.trvl-media.com/hotels/36000000/35370000/35361600/35361543/c1b09391_z.jpg"
          >
            <v-card-title>Vip Room</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://pix10.agoda.net/hotelImages/162/1621440/1621440_16111613200048769102.jpg?s=1024x768"
          >
            <v-card-title>Room 1</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://d2ile4x3f22snf.cloudfront.net/wp-content/uploads/sites/282/2018/04/23070030/Room-1.jpg"
          >
            <v-card-title>Room 2</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://cdn.renthub.in.th/images/uploaded/201912/20191224/apartment_pictures/normal/7a6943eba16dccf704a9ad32b3c4c056.jpg?1577171939"
          >
            <v-card-title>Room 3</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://www.anskkhotel.com/wp-content/uploads/2019/07/Amnauysuk_room_StandardSingle_5.jpg"
          >
            <v-card-title>Room 4</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://cf.bstatic.com/images/hotel/max1024x768/228/228996550.jpg"
          >
            <v-card-title>Room 5</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
        <v-card
          class="ma-3 mx-auto"
          max-width="250"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="https://www.lkpattaya.com/residence/images/Two-Bedroom-Suite_1.jpg"
          >
            <v-card-title>Room 6</v-card-title>
          </v-img>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              depressed
              color="primary"
            >
              Previwe
            </v-btn>
            <v-spacer />

            <v-btn icon color="error">
              <v-icon>mdi-heart</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-bookmark</v-icon>
            </v-btn>

            <v-btn icon>
              <v-icon>mdi-share-variant</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-row>
    </v-card>
  </v-card>
</template>

<script>

export default {
  components: {

  }
}
</script>
