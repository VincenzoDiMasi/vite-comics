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
        <div class="container">
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
        </div>
    </section>
    <section id="c2a-footer-section"></section>
</footer>
  
</template>

<style lang="scss" scoped>
#navbar-footer-section {
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 285px;

    .container {
        display: flex;

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
    }
    }
        
}
#c2a-footer-section {
    height: 100px;
    background-color: rgb(48, 48, 48);
}


</style>