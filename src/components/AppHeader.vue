<template>
    <header class=" wrapper">
        <div>
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div>
            <ul class="flex">
                <li v-for="links in headerNavbar" :class="links.selected ? 'selected' : ''">
                {{ links.text }}
                </li>
            </ul>
        </div>
    </header>
</template>

<script>
export default{
        data() {
            return{
                headerNavbar : [
                    {
                        text: "CHARACTERS",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "COMICS",
                        link: "#",
                        selected: true
                    },
                    {
                        text: "MOVIES",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "TV",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "GAMES",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "COLLECTIBLES",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "VIDEOS",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "FANS",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "NEWS",
                        link: "#",
                        selected: false
                    },
                    {
                        text: "SHOP",
                        link: "#",
                        selected: false
                    },
                ],

            }
        }
    }
</script>

<style scoped>


header{
   
    margin: auto;
    padding: 15px 0 15px;
    display: flex;
    justify-content: space-between;

   

}

img{
    height: 80px;
}

li{
    padding-left: 30px;
    font-size: .85rem;
    font-weight: 700;
    color: #1C1C1C;
    list-style: none;
}

.selected{
    color: #0282F9;
}
    
ul{
    display: flex;
}
</style>