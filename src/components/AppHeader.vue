<template>
    <header>
        <div class="logo-container">
            <img src="../assets/img/dc-logo.png" alt="logo-dc" class="logo">
        </div>
        <div class="navbar-container">
            <ul>
               <li>characters</li>
               <li class="active">comics</li>
               <li>movies</li>
               <li>tv</li>
               <li>game</li>
               <li>collectibles</li>
               <li>videos</li>
               <li>fans</li>
               <li>news</li>
               <li>shop</li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    
    name: 'AppHeader',
    data(){
        return{
            navbarElements : ["characters" , "comics" , "movies" , "tv" , "game" , "collectibles" , "videos" , "fans" , "news" , "shop"]
        }
    }
}
</script>

<style lang="scss" scoped>
.logo-container{
    
    width: 35%;
    text-align: center;
    padding: 1rem;
}

.logo{
    height: 80px;
}

header{
    display: flex;
}

ul{
    list-style: none;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}

.navbar-container{
    width: 65%;
    padding: 1.2rem;
    
}

li{
    margin-right: 1rem;
    font-size: 1.2rem;
    
}

.active{
    border-bottom: 6px solid cornflowerblue;
}
</style>