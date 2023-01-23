<script>
export default {
    name: 'AppFooter',
    data() {
    return {

    }
  },
  
}
</script>

<template>
<footer>
    <section id="navbar-footer-section">
        <div class="container flex">
            <div class="nav-footer">

                <h2>DC COMICS</h2>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                </ul>
                <h2>SHOP</h2>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                </ul>
            </div>
            <div class="nav-footer">
                <h2>DC</h2>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                </ul>
            </div>
            <div class="nav-footer">
                <h2>SITES</h2>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                
                </ul>
            </div>
            <!-- <img src="../assets/img/dc-logo-bg.png" alt="dc-logo-big"> -->
        </div>
    </section>
    <section id="c2a-footer-section">
        <nav class="container flex">
                <div class="nav-left">
                    <button>SIGN-UP NOW!</button>
                </div>
                <div class="nav-right flex">
                    <span>FOLLOW US</span>
                    <ul class="flex">
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a></li>
                    </ul>
                </div>
            </nav>
    </section>
</footer>
  
</template>

<style lang="scss" scoped>

.flex {
    display: flex;
}

#navbar-footer-section {
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 285px;

    .container {
        

        .nav-footer {
        height: 285px;
        min-width: 100px;
        // border: 1px dashed white;
        color: gray;
        font-size: 12px;
        margin-right: 15px;

        li {
            margin-bottom: 1px;

            
        }

        

        h2 {
            color: white;
            padding: 35px 0 15px 0;
        }

        a {
            color: gray;
            font-size: 10px;
            
        }

        // img {
        //     height: 80px;
        // }
    }
    }
        
}
#c2a-footer-section {
    height: 100px;
    background-color: rgb(48, 48, 48);
    padding-top: 35px;

    .container {
        
        justify-content: space-between;

        .nav-right {
            display: flex;

            li {
                margin-right: 8px;
            }

            span {
                margin-top: 7px;
                margin-right: 15px;
                color: dodgerblue;
                font-weight: bold;

            }

        }

        .nav-left {

            button {
                padding: 7px;
                border: 3px solid dodgerblue;
                background-color: transparent;
                color: white;
                font-weight: bold;
                cursor: pointer;
            }
        }
    }
}



</style>