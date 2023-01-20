<script>
export default {
    name: 'AppHeader',
    data() {
    return {
        navbarLinks: [
        {
            text: 'Characters',
            url: '#',
            current: false,
        },
        {
            text: 'Comics',
            url: '#',
            current: true,
        },
        {
            text: 'Movies',
            url: '#',
            current: false,
        },
        {
            text: 'TV',
            url: '#',
            current: false,
        },
        {
            text: 'Games',
            url: '#',
            current: false,
        },
        {
            text: 'Collectibles',
            url: '#',
            current: false,
        },
        {
            text: 'Videos',
            url: '#',
            current: false,
        },
        {
            text: 'Fans',
            url: '#',
            current: false,
        },
        {
            text: 'News',
            url: '#',
            current: false,
        },
        {
            text: 'Shop',
            url: '#',
            current: false,
        }
        ]
    }
  },
}
</script>

<template>
<header>
    <div class="container">
        <figure>
            <a href="#"><img src="../assets/img/dc-logo.png" alt=""></a>
        </figure>
        <nav>
            <ul>
                <li v-for="navbarLink in navbarLinks" :key="navbarLink.text"><a :href="navbarLink.url" :class="{ 'active': navbarLink.current }">{{ navbarLink.text }}</a></li>
            </ul>
        </nav>
        
    </div>
    
</header>
  
</template>

<style lang="scss" scoped>
header {
    background-color: white;
    height: 100px;
    // display: flex;
    
}



.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

img {
    margin-top: 15px;
    height: 70px;
    
}

nav {
    ul {
        display: flex;
        gap: 1.5rem;

        li {
            a {
                text-transform: uppercase;
                color: grey;
                font-size: 12px;
                font-weight: bold;
                

                &.active {
                    color: dodgerblue;
                    border-bottom: 2px solid dodgerblue;
                }
                
            }
        }
    }

}


</style>