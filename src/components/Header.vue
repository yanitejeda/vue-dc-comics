<template>
    <div class="header-box container ">
        <div class="box-logo-header">
            
            <img alt="dcHeaderLogo" src="../assets/dc-logo.png">

        </div>
        <div>
            <ul class="list-group">
                <li class="navbar-item singleB" v-for="(item, i) in navbarMenu" :key="i">
                    {{item.tittle}}
                </li>
            </ul>
        </div>

       
    </div>
</template>

<script>
export default{
    name : "Header",
    data(){
        return {
            navbarMenu:[
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
                    tittle :"COLLECTIBLES"
                }, {
                    tittle :"VIDEOS"
                }, {
                    tittle :"FANS"
                }, {
                    tittle :"NEWS"
                }, {
                    tittle :"SHOP"
                },
            ]
        }
    }

}

</script>
