<template>
    <header>
        <div class="logo-container">
            <img src="../assets/img/dc-logo.png" alt="logo-dc" class="logo">
        </div>
        <div class="navbar-container">
            <ul>
                <li v-for="">

                </li>
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
</style>