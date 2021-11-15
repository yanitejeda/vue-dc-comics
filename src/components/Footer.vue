<template>
    <div>
            <!-- sezione finale del footer -->
        <div class="main-footer">
            <div class="flexF container">

               <div class="listGroup">
                   <div>
                        <ul>
                            <h5>Dc comics</h5>
                            <li v-for="(item, i) in dcComics" :key="i">
                                {{item.tittle}}
                                <!-- lista loghi footer -->
                            </li>

                            <h5>Shop</h5>
                            <li v-for="(item, i) in shop" :key="i">
                                {{item.tittle}}
                                <!-- lista loghi footer -->
                            </li>
                        </ul>
                    </div>

                    <div>
                        <ul>
                            <h5>Dc</h5>
                            <li v-for="(item, i) in dc" :key="i">
                                {{item.tittle}}
                                <!-- lista loghi footer -->
                            </li>
                        </ul>
                    </div>

                    <div>
                        <ul>
                        <h5>Sites</h5>
                        <li v-for="(item, i) in site" :key="i">
                            {{item.tittle}}
                            <!-- lista loghi footer -->
                        </li>
                        </ul>
                    </div>
               </div>
               <div class="logo-bg">
                 <!--   <img :src="require('@/assets/dc-logo-bg.png')" alt="">
              -->  </div>
            </div>
        </div>

        <div class="barFooter">
           <!-- sezione grigia con sinh-up e logo footer -->
          <div class="container box">
               <div>
                 <button class="btn-footer">SING-UP NOW!</button>
               </div>

                <div class="listGroupIon">
                    <h5 class="btn-b">FOLLOW US</h5>
                    <ul class="socialIcon">
                        <li>
                            <img :src="require('@/assets/footer-facebook.png')" alt="">
                            <img :src="require('@/assets/footer-twitter.png')" alt="">
                            <img :src="require('@/assets/footer-youtube.png')" alt="">
                            <img :src="require('@/assets/footer-pinterest.png')" alt="">
                            <img :src="require('@/assets/footer-periscope.png')" alt="">   
                        </li>
                    </ul>
                </div>
          </div>
        </div>
    </div>
</template>

<script>
export default{
    name : "Footer",
    data(){
        return {
            dcComics:[
                {
                    tittle :"CHARACTERS"
                },
                 {
                    tittle :"COMICS"
                }, {
                    tittle :"MOVIES"
                }, {
                    tittle :"TV"
                }, {
                    tittle :"GAMES"
                }, {
                    tittle :"VIDEOS"
                },{
                    tittle :"NEWS"
                },
            ],

            shop:[
                 {
                    tittle :"Shop DC"
                }, {
                    tittle :"Shop DC Collectiblea"
                },
            ],
               dc:[
                 {
                    tittle :"Terms Of Use"
                }, {
                    tittle :"Privacy policy (New)"
                },  {
                    tittle :"Ad Choices"
                }, {
                    tittle :"Advertising"
                },  {
                    tittle :"Jobs"
                }, {
                    tittle :"Subscritions"
                },
                {
                    tittle :"Telent Workshops"
                },  {
                    tittle :"CPSC Certificates"
                }, {
                    tittle :"Rating"
                },{
                    tittle :"Shop Help"
                },  {
                    tittle :"Jobs"
                }, {
                    tittle :"Contact Us"
                },
            ],
             site:[
                 {
                    tittle :"DC"
                }, {
                    tittle :"MAD Magazine"
                },  {
                    tittle :"DC Kids"
                }, {
                    tittle :"DC Universe"
                },  {
                    tittle :"DC Power Visa"
                }, 
            ],
        }
    }

}

</script>
