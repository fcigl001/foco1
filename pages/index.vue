<template>
  <v-container fluid class="bg" style="object-fit: cover">
    <v-row>    
      
      <v-col cols="12">
        <!-- <v-responsive class="bg" aspect-ratio="2.6"></v-responsive> -->
                 <h1 class="txtTop">
                Empowering Property Investment <br>Advice Professionals
               </h1>
             
              <h4 class="txtTop1">
                Become a Master Property Investment Advisor, <br>unlock opportunitie and help your clients<br> make informed decisions with PIERS.
              </h4>
       
                <v-img class="align-left"
                  lazy-src="/image/PIERS_forDarkBG.png"
                  max-height="5rem"
                  src="/image/pierslogo.png"
                  ></v-img>
             
                  <v-container class="d-flex align-left flex-column flex-sm-row txtTop2">
                    <v-btn
                    width="300px"
                    color="indigo"
                  >
                    Find out more...
                  </v-btn>
                 </v-container>

              </v-col>       
            </v-row>
  </v-container>
  <v-container>
      <v-row>
        <v-col cols="6" xs="12" md="6">
          <v-sheet>


            <v-card  outlined flat>
              <v-card-text>
                <v-card-title class="mb-5 text-h4 font-weight-black" color="green">Are you one of the following professionals?</v-card-title>
                    <v-alert class="mb-2"
                    border="start"
                      density="comfortable"
                      type="success"
                      variant="tonal"
                    >
                    <span v-html="item1"> </span>
                    </v-alert>
                    <v-alert class="mb-2"
                    border="start"
                      density="comfortable"
                      type="success"
                      variant="tonal"
                    >
                    <span v-html="item2"> </span>
                    </v-alert>
                    <v-alert
                    border="start"
                      density="comfortable"
                      type="success"
                      variant="tonal"
                    >
                    <span v-html="item3"> </span>
                    </v-alert>
                    <p class="mt-5">
                      We have developed a new platform for advisors. We call it the Property Investment Evaluation and Research System, (PIERS).
                     </p>
                     <p class="mt-5">
                      But we don't just offer software. We have training, mentoring and support for you to create a successful business by those who have been using it for years with great results.
                     </p>
                      <v-btn color="primary"
                      plain
                      outlined
                 
                        elevation="2"
                        large class="mt-5 pa-3"> Find out more here!</v-btn>
              </v-card-text>
            </v-card>
          </v-sheet>    
        </v-col>
        <v-col cols="6" xs="12" md="6">
          <v-sheet class="ma-2 pa-2">
            <v-card outlined flat min-width="700">
              <v-card-title class="mb-5 text-h4 font-weight-black" color="green">About PIERS:</v-card-title>
              <v-card-text>
              <video-player width=680px
                  src="/image/FCIGL_PIERS_V1.mp4"
                  poster="/image/PIERS_forDarkBG.png"
                  controls
                  :loop="false"
                  :volume="0.6"
                />
              </v-card-text>
             
              </v-card>
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
        <v-row style="margin-top: -50px">
          <v-col>
            <v-card outline flat>
              <v-img
                lazy-src="/image/check_list.png"
                max-height="400"
                src="/image/check_list.png"
                ></v-img>
            </v-card>
          </v-col>
            <v-col>
              <v-card outlined flat>
                <v-sheet>
             <v-card class="ma-5" outlined flat>
               <v-card-title class=" purple yellow--text text--darken-2"><b>
                 Property Investment Advice Made Simple
 
               </b>
             </v-card-title>
               <v-card-text class="blue lighten-5">
            <p class="cyan-lighten-4">
              When it comes to providing value for your clients, are you consistent in delivering results? You're not alone if not.
 
            </p>
            
             <p>
               It's important to focus on reliability and consistency, especially 
               in the current climate. That's why we've been utilizing a
               tried-and-true system that has been producing results for over two decades!
             </p>
             <p>
               This system can help you create a framework for reliable results
               no matter what kind of market you are dealing with. Take advantage
               of the resources available now to find out how this system can be
               used to produce positive outcomes for you and your clients!
             </p>
               </v-card-text>
               </v-card>
           </v-sheet>

              </v-card>
              
            </v-col>
      </v-row>
      <v-row>
        <!-- <h1 class="ml-5 mb-5">Software Features:</h1> -->
      </v-row>
      <v-row>
        <v-col>

          <v-card>
            <v-card-title class="text-h4 font-weight-black txt1">
              Research</v-card-title>
              <v-card-text>
            <v-img
              lazy-src="/image/check_list.png"
              max-height="300"
              src="/image/check_list.png"
              ></v-img>
              <v-alert class="mb-2"
              border="start"
                      density="comfortable"
                      type="success"
                      variant="tonal"
                    >
                    <span v-html="item20"> </span>
                    </v-alert>
                  
          </v-card-text>
          </v-card>
        </v-col>
        <v-col>
          <v-card> <v-card-title class="text-h4 font-weight-black txt1">Evaluate</v-card-title>
          <v-card-text>
            <v-img
              lazy-src="/image/check_list.png"
              max-height="300"
              src="/image/check_list.png"
              ></v-img>
              <v-alert class="mb-2"
                      density="comfortable"
                      type="info"
                      variant="tonal"
                    >
                    <span v-html="item26"> </span>
                    </v-alert>
                    <v-alert class="mb-2"
                      density="comfortable"
                      type="info"
                      variant="tonal"
                    >
                    <span v-html="item27"> </span>
                    </v-alert>
                    <v-alert class="mb-2"
                      density="comfortable"
                      type="info"
                      variant="tonal"
                    >
                    <span v-html="item28"> </span>
                    </v-alert>
          </v-card-text>
          </v-card>
          
        </v-col>
        <v-col>
          <v-card><v-card-title class="text-h4 font-weight-black txt1">Optimise</v-card-title>
            <v-card-text>
            <v-img
              lazy-src="/image/check_list.png"
              max-height="300"
              src="/image/check_list.png"
              ></v-img>
              <v-alert class="mb-2"
                        density="comfortable"
                      type="info"
                      variant="tonal"
                        >
                        <span v-html="item29"> </span>
                        </v-alert>
                        <v-alert class="mb-2"
                        density="comfortable"
                      type="info"
                      variant="tonal"
                        >
                        <span v-html="item30"> </span>
                        </v-alert>
          </v-card-text>
          </v-card>
          
        </v-col>
      </v-row>
      <h1 class="ml-5 mb-5 mt-6 txt">How to's:</h1><br>
      <v-row nowrap>
        <v-col >
          <v-card md6>
              <v-card-title class="type1">
                CREATE A PROPERTY REPORT:</v-card-title>
            </v-card>

        </v-col>
      </v-row>
      </v-container> 

      <v-layout row >
        <v-flex md6>
          <v-card>
            <v-img
              lazy-src="/image/check_list.png"
              max-height="500"
              src="/image/check_list.png"
              ></v-img>
          </v-card>
      </v-flex>
      <!-- <v-flex md6>
        <v-card class="mr-3 pl-5 pt-3">
          <h2 class="pb-3 pl-3">Are You?</h2>
          <v-layout row wrap>
            <v-flex>
              <span>
                <v-list :disabled="true" class="mr-3">
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="./arrow.svg"></v-img>
                    </v-avatar>

                    <v-list-item-content v-html="item1"> </v-list-item-content>
                  </v-list-item>
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="./arrow.svg"></v-img>
                    </v-avatar>
                    <v-list-item-content v-html="item2"> </v-list-item-content>
                  </v-list-item>
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="./arrow.svg"></v-img>
                    </v-avatar>
                    <v-list-item-content v-html="item3"> </v-list-item-content>
                  </v-list-item>
                </v-list>
                <h2 class="pb-3 pl-3">
                  Then Forrester Cohen can help <i>YOU...</i>
                </h2>
                <p v-html="item4" class="pb-3 pl-3"></p>
                <v-list :disabled="true" flat class="mr-3">
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-icon>email</v-icon>>
                    </v-avatar>

                    <v-list-item-content v-html="item5"> </v-list-item-content>
                  </v-list-item>
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="/image/icon.png"></v-img>
                    </v-avatar>
                    <v-list-item-content v-html="item6"> </v-list-item-content>
                  </v-list-item>
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="/image/icon.png"></v-img>
                    </v-avatar>
                    <v-list-item-content v-html="item7"> </v-list-item-content>
                  </v-list-item>
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="/image/icon.png"></v-img>
                    </v-avatar>
                    <v-list-item-content v-html="item8"> </v-list-item-content>
                  </v-list-item>
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="/image/icon.png"></v-img>
                    </v-avatar>
                    <v-list-item-content v-html="item9"> </v-list-item-content>
                  </v-list-item>
                  <v-list-item>
                    <v-avatar class="pr-2 pb-2" height="30px" width="30px">
                      <v-img src="/image/icon.png"></v-img>
                    </v-avatar>
                    <v-list-item-content v-html="item10"> </v-list-item-content>
                  </v-list-item>
                </v-list>
                <v-flex class="pb-3 pl-5">
                  <span>
                    <p>
                      Our advice platform, allows you to focus on your business
                      promise to your clients. We want to make it as effective
                      as we can - to let you concentrate on what's important -
                      your customer!
                    </p>
                    <p>
                      Use this tried and proven system to produce reliable
                      results for your clients. Its a system that has produced
                      consistent results for over 20 years in a variety of
                      markets.
                    </p>
                    <p>
                      For more than 10 years, we have been helping advisors
                      create wealth for their clients.
                    </p>
                    <p>
                      So, if you want to enhance your reputation, strengthen
                      your relationships and create better results, join us by
                      clicking the link below!
                    </p>
                  </span>
                </v-flex>
              </span>
            </v-flex> 
          </v-layout>
        </v-card>
      </v-flex> -->
      </v-layout>
  
</template>
<script>
  import { defineComponent } from 'vue'
  import { VideoPlayer } from '@videojs-player/vue'
  import 'video.js/dist/video-js.css'

  export default defineComponent({
    components: {
      VideoPlayer
    },
    data() {
      return {
        dialog: false,
      firstname: '',
      email: '',
      statement: `PIERS is Forrester Cohen's Property Investment Evaluation and Research System`,
      item1: `<p style="font-size: 18px; ">An <strong>Advice Professional,</strong> delivering property investment advice to business standards?</p>`,
      item2: `<p style="font-size: 18px; ">A <strong>Mortgage Broker</strong>, who wants to add quality property services for your clients, to create greater lifetime value?</p>`,
      item3: `<p style="font-size: 18px;">Or, a <strong>Property Investment Advisor</strong> wanting to deliver more to engage their clients for a life time?</p>`,
      item4: `<p style="font-size: 20px; margin-top: 20px; margin-bottom: 20px"><b>We have developed a new platform for advisors. We call it the Property Investment Evaluation and Research System, (PIERS).</b></p>`,
      item5: `<p style="font-size: 20px;">Analyse pre vetted projects to give you confidence in the financial results.</p>`,
      item6: `<p style="font-size: 20px;">Research and identify the better performing areas showing your expertise.</p>`,
      item7: `<p style="font-size: 20px;">Create and maintain client profiles so you can create  personalised results..</p>`,
      item8: `<p style="font-size: 20px;">Generate professional analysis reports, fast to allow you to deliver more.</p>`,
      item9: `<p style="font-size: 20px;">Design property investment portfolios for testing outcomes, to create better results.</p>`,
      item10: `<p style="font-size: 20px;">and then, you can  secure property meeting your thorough evaluation criteria.</p>`,
      item11: `<p>Our advice platform, allows you to focus on your business
                      promise to your clients. We want to make it as effective
                      as we can - to let you concentrate on what's important -
                      your customer!</p>`,
      item12: `<p style="font-size: 20px;">Developers and builders are selected for their reputation in
                delivering what they promise.</p> `,
      item13: `<p style="font-size: 20px;">You don’t miss out on commissions or fees from disreputable
                players. Enforyoceable Legal agreements are in place for the
                provision of commissions.</p>`,
      item14: `<p style="font-size: 20px;">Access full commissions with relevant Real Estate license OR use
                an optional listing agent and access majority of fees.</>`,
      item15: `<p style="font-size: 20px;">Properties are selected for potential performance on cash flow or capital growth.</>`,
      item16: `<p style="font-size: 20px;">Create Property Analysis (PIA) Reports on individual properties quickly and easily.</>`,
      item17: `<p style="font-size: 20px;">Model portfolios to demonstrate potential outcomes and stress test them for clients.*</>`,
      item18: `<p style="font-size: 20px;">Transaction management service: Our team can manage your back of house services from EOI through construction to rental management for your clients. This service keeps you as the client facing advisor.*</p>`,
      item19: `<p style="font-size: 20px;">Regular independent research reports are published on key areas
              that are factual, dated and referenced for you to present to the
              client.*</p>`,
      item20: `<p style="font-size: 18px;">PIERS provides the <b>information and data</b> to give you a  better understanding of the market and area you are interested in investing.</p><br><p style="font-size: 18px;"> Study market trends, demographic data, local economic indicators, and our <b>proprietary indicators</b> that impact the value and performance of a property.</p> <br><p style="font-size: 18px;">Let us help you determine whether a specific property is a good investment opportunity.</p>`,
      // item21: `<p style="font-size: 14px;"><strong>Days on Market with Median Price</strong> over 12 months and 5 years</p>`,
      // item22: `<p style="font-size: 14px;"><strong>Rental yields</strong></p>`,
      // item23: `<p style="font-size: 14px;"><strong>Stock on market</strong>.</p>`,
      // item24: `<p style="font-size: 14px;"><strong>Demographics</strong></p>`,
      // item25: `<p style="font-size: 14px;"><strong>Sales data</strong> and more....</p>`,
      item26: `<p style="font-size: 16px;"><strong>Evaluate</strong> potential ROI.</p>`,
      item27: `<p style="font-size: 16px;"><strong>Evaluate</strong> performance and risk.</p>`,
      item28: `<p style="font-size: 16px;"><strong>Evaluate</strong> market trends and economic conditions.</p>`,
      item29: `<p style="font-size: 16px;"><strong>Assess</strong> cash flow and rental income.</p>`,
      item30: `<p style="font-size: 16px;"><strong>Simulate, monitor and adjust</strong> the performance of your portfolio.</p>`,
      item31: `<p style="font-size: 16px;"><strong>Simulate, monitor and adjust</strong> the performance of your portfolio.</p>`,
      }
    }
  })
</script>
 
<style scoped>
 .bg {
 background-position: right;
  width: 100vw;
  height:40vh;
  background-image: 
    linear-gradient(rgba(89, 123, 176, 0.9), rgba(204, 215, 225, 0.3)),
    url('/image/Buildings.jpeg') !important;
 
} 
.tt {
  margin-top: 100px;
  margin-left: 0px;
  margin-right: 0px;
  line-height: 60px;
  font-size: 54px;
}
.align-left {
    float: left;
    margin-right: 1rem;
  }
.t2 {
  margin-top:2px;
  font-size: 34px;
}
.t3 {
  font-size: 26px;
}
/*.h2 {
  font-family: Fira Sans;
}*/
.image {
  content: center;
}
ul {
  list-style: none;
}
.ic {
  size: 20px;
  fill: #00cc00;
}
.v-card__text,
.v-card__title {
  word-break: normal; /* maybe !important  */
  font-size: 40px;
}

.lh {
  /* line-height: 30px; */
}
.txt {
  color: #2196F3;
}
.txt1 {
  color: #1976c2;
}
.txtTop {
  color: #ffffff;
  text-align: left;
  margin-left: 10vw;
  font-size: 2.8rem;
  line-height: 2.9rem;
}
.txtTop1 {
  color: #0b5592;
  padding-top: 20px;
  margin-left: 10vw;
  padding-bottom: 20px;
  text-align: left;
  font-size: 1.3rem;
  line-height: 1.6rem;

}
.txtTop2 {
  color: #0b5592;
  text-align: left;
  margin-left: 9vw;
  font-size: 1.3rem;
  line-height: 1.6rem;
  float: left;

}
li.shield {
  background: url('/2.png') no-repeat left top;
  line-height: 20px;
  min-height: 50px;
  padding-left: 44px;
  padding-right: 50px;
  padding-top: 3px;
  display: block;
}
ul.no_bullet {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
p {
  font-size: 18px;
  line-height: 24px;
  margin-bottom: 10px;
  margin-right: 10px;
}
.rhs-text {
  font-size: 16px;
}
</style>
