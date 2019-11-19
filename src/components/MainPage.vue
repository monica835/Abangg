<template>
<div>
  <Header></Header>
  <v-card class="d-inline-block mx-auto">
    <section class="search-sec">
      <form action="#" method="post" novalidate="novalidate">
        <div class="row">
          <div class="col-lg-12">
            <div class="row">
              <div class="col-lg-3 col-md-3 col-sm-12 p-0">
                 <div class="form-control search-slt">
                <v-select :items="items" placeholder="choose your options"  standard></v-select>
                </div>
              </div>
              <div class="col-lg-3 col-md-3 col-sm-12 p-0">
                <div class="form-control search-slt">
                <input type="text" placeholder="location" />
                </div>                           
              </div>
              <div class="col-lg-3 col-md-3 col-sm-12 p-0">
                <div class="form-control search-slt">
                  <input type="date" v-model="date" class="one" />
                </div>
              </div>
               <div class="col-lg-3 col-md-3 col-sm-12 p-0">
                <div class="form-control search-slt">
                  <input type="date" v-model="date" class="two" />
                </div>
              </div>
              <div class="col-lg-3 col-md-3 col-sm-12 p-0">
                <button type="button" class="btn btn-primary wrn-btn" @click="search()"><a class="fa fa-search">Search</a></button>
              </div>
            </div>
          </div>
        </div>
      </form>
    </div>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQY5n7aZgbqT4cCtgMxQqDk3nw5Nht5fR4BbzGsIrP8k877smse&s"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://www.cartrack.co.za/sites/default/files/car.jpg"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://stimg.cardekho.com/images/carexteriorimages/630x420/Kia/Kia-Seltos/6232/1562746799300/front-left-side-47.jpg?tr-371,e-sharpen"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQQs7kaoUewSBHa7T6rUyWHNdqUuKnCwvuAAexV7xdkPy4w4a2D&s"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://hondaph.com/wp-content/uploads/2019/09/XRM_MOTARD_RED.png"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://d2pa5gi5n2e1an.cloudfront.net/global/images/product/motorcycle/Honda_Wave_125/Honda_Wave_125_L_1.jpg"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://southwesttours.ph/media/catalog/product/cache/1/image/700x700/9df78eab33525d08d6e5fb8d27136e95/v/a/van_6_2.png"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://static.wixstatic.com/media/2a66ae_08c1ea91371d4602bc214a21a6d46d7e~mv2.jpg/v1/fill/w_838,h_558,al_c,lg_1,q_85/2a66ae_08c1ea91371d4602bc214a21a6d46d7e~mv2.jpg"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="http://toyota.com.ph/wp-content/uploads/2018/06/HH1303-F-01.png"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://www.comparabus.com/bundles/static/uploads/FlixBus/flixbus-bus-pas-cher.png"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-o1gYHkr_RZqc8fSsRRqVkTzI4rnNTnNIPMRGDy6pkCyKycgB&s"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTJAYN7q44EQTpXGCeRGgm8jg3lMt-MXZIsgp0N_TQCOdm1KewU&s"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8LkhXzxAXZj8qR4D6rM7QJYMeKtUPlQhzoriPu10GPv4mWOYg&s "
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgxfeR566GQF0vDZJvqq_JZp0ZQAZ-XzCuSkCYVlI717nN-79S&s"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="250"
            width="300"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQy2ZJL8FOtHn4M6PA47oVHv_unF7nIUHEzWLn2SXluKq0btbv4&s"
          ></v-img>
        </v-col>
        <v-col class="mb-3">
          <h1>FNDSajufasdf</h1>
          <v-btn class="primary" @click="reserved()">Reserved</v-btn>
        </v-col>
        <v-col cols="auto" class="text-center pl-0">
          <v-row class="flex-column ma-0 fill-height" justify="center">
            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </v-col>

            <v-col class="px-0">
              <v-btn icon>
                <v-icon>mdi-share-variant</v-icon>
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </v-card>
  </div>
</template>
<script>
import Header from "../components/Header.vue"
export default {
  components:{
    Header
  },
  data() {
    return {};
  },
  methods: {
    reserved() {
      this.$router.push("/Login");
    }
  }
};
</script>
<style scoped>
.container {
  border: #1976d2 3px solid;
  margin-top: 100px;
  width: 450%;
  margin-left: 10px;
}
.v-card:not(.v-sheet--tile):not(.v-card--shaped) {
  border-radius: 4px;
  width: 146%;
  margin-top: 50px;
}
.row {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-flex: 1;
    -ms-flex: 1 1 auto;
    flex: 1 1 auto;
    margin-right: -12px;
    margin-left: -12px;
    margin-top: 50px;
}

</style>