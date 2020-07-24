<template>
  <v-container>
    <v-row class="text-center" justify="center">
      <v-col cols="12" class="text-center" justify="center">
        <v-row>
          <v-col><h1 style="text-align:center;">自由に生きる<br>クリエイター集団</h1><br><h4>夢中という武器でプロジェクトを救う集団</h4></v-col>
        </v-row>
      </v-col>
      <v-col cols="12" sm="6">
        <v-img src="../assets/1_00_0718_6.svg"></v-img>       
    </v-col>
    </v-row>
      <v-row class="text-center"  justify="center" align-content="center" style="padding-bottom:5%;">
      
      <v-col cols="12" sm="6" style="padding-top:5%;">
        <v-col justify="center" align-content="center"><v-img src="../assets/service_1.png"></v-img></v-col>
       
      </v-col>
      <v-col cols="12" sm="6" style="padding-left:5%;" class="text-left" justify="center" align-content="center">
        <v-row>
          <v-col>
            <h3>ABOUT</h3>
       <h2 style="padding-top:2%;">テクノロジーを通じて<br>要望を叶える + 感動を与える</h2><br>BPIは受託事業をはじめ、依頼いただいてるお客様に、
       デザイン、プログラミング 、サーバー構築など、あらゆるものづくりの分野で問題・課題が解決できるご提案をさせていただいております。</v-col>
        </v-row>
        <v-row>
          <v-col cols="4">
           <v-img src="../assets/service_2.png"></v-img>
           </v-col>
                     <v-col cols="4">
           <v-img src="../assets/service_3.png"></v-img>
           </v-col>
                     <v-col cols="4">
           <v-img src="../assets/service_4.png"></v-img>
           </v-col>
        </v-row>
      </v-col>
    </v-row>
          <v-row flex-md-fill class="text-center" style="background-color:#06625B;color:#fff;padding:5%;">
      <v-col cols="12" sm="6">
       <v-col class="text-left" justify="center" align-content="center">
       <h2>得意分野がバラバラ。<br>だから光るものがある。</h2><br>BPIは受託事業をはじめ、依頼いただいてるお客様に、
       デザイン、プログラミング 、サーバー構築など、あらゆるものづくりの分野で問題・課題が解決できるご提案をさせていただいております。</v-col>
       </v-col>
      <v-col cols="12" sm="6">
        ここにメンバー紹介イラストが入ります。
      </v-col>
    </v-row>
          <v-row class="text-center">
      <v-col cols="12">
        ここに協力会社が入ります。
      </v-col>
    </v-row>
           <v-row flex-md-fill class="text-center" style="background-color:#333;color:#fff;padding:5%;">
             <v-col cols="12" sm="6" >
       <v-col class="text-left" justify="center" align-content="center">
       <h4 style="line-height:2rem;">会社概要｜Company Profile<br>
有限会社B.P.I（ビーピーアイ）<br>
平成17年8月12日設立<br>
資本金300万円<br>
神奈川県横浜市鶴見区生麦3-7-10<br>
京浜急行線「生麦駅」徒歩1分<br>
(045) 501-2783<br>
info@bpi.yokohama<br>
bpi.yokohama</h4></v-col>
       </v-col>
      <v-col cols="12" sm="6">
          <v-col justify="center" align-content="center"><v-img src="../assets/people_1_6.png"></v-img></v-col>
      </v-col>
    </v-row>
         
          <v-row class="text-center">
      <v-col cols="3">
        ここにお問い合わせボタンが入ります。
      </v-col>
      <v-col cols="9">
        ここにフッターが入ります。
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
