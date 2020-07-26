<template>
  <v-container fluid>
    <v-row style="margin-top:5%;" class="text-center" justify="center">
      <v-col cols="12">
          <v-row  justify="center">
          <v-col cols="4" sm="2"><v-img src="../assets/rogo.svg"></v-img>
            </v-col>
            </v-row>
          <h5>「プロジェクト」を救うクリエイター集団
          </h5>
      </v-col>
      <v-col cols="12" sm="6">
        <v-img src="../assets/1_00_0718_8.svg"></v-img>       
    </v-col>
    </v-row>
      <v-row style="margin-top:20%;">
 　　　<v-col cols="10">
        <v-col cols="6">
      <h3>ABOUT</h3>
       <h1 style="padding-top:2%;">テクノロジーを通じて<br>要望を叶える + 感動を与える</h1>
               <v-col  style="font-size:14px;"> 
       BPIは受託事業をはじめ、依頼いただいてるお客様に、
       デザイン、プログラミング 、サーバー構築など、あらゆるものづくりの分野で問題・課題が解決できるご提案をさせていただいております。
     
       </v-col> 
        </v-col>
        
        <v-col  cols="1" style="margin-top:15%;">
          <v-img src="../assets/service_1.png"></v-img>
        </v-col>
        </v-col>
   

       <v-col cols="12" style="padding-top:5%;">
         <v-row  justify="center" class="text-center">
          <v-col cols="3" style="padding:5%;">
            <h2 style="padding-bottom:10px;">1</h2>
           <v-img src="../assets/service_2.png"></v-img>
           <h4 style="padding-bottom:20px;">受託制作事業</h4>
           <span style="font-size:14px;line-height:16px;">チラシ、ロゴ、HP制作、システム開発などクリエイティブの分野で制作いたします。</span>
           
           </v-col>
            <v-col cols="3" style="padding:5%;">
            <h2 style="padding-bottom:10px;">2</h2>
           <v-img src="../assets/service_3.png"></v-img>
           <h4 style="padding-bottom:20px;">SES事業</h4>
           <span style="font-size:14px;line-height:16px;">デザインやプログラミングスキルを通じて、お客様プロジェクトをお手伝いしします。</span>
       
           </v-col>
            <v-col cols="3" style="padding:5%;">
               <h2 style="padding-bottom:10px;">3</h2>
           <v-img src="../assets/service_4.png"></v-img>
           <h4 style="padding-bottom:20px;">電気工事業</h4>
           <span style="font-size:14px;line-height:16px;">LAN、照明、テレビアンテナなど、弱電工事を承ります。</span>
  
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
