<script>
export default {
    data() {
        return {
            //  navSections: [

            //       {
            //         name: "dcComics",
            //         navLinks: [
            //              "characters","comics","movies","tv","games","collectibles","videos", "fans", "news", "shop"
            //         ] 
            //     },

            //      {
            //         name: "shop",
            //          navLInks: [ "Shop DC", "Shop DC Collectibles"]
            //     },

            //     { name: "dc",
            //         navLinks: ["Terms of Use","Privacy Policy", "Ad choices"]
            //     }
            // ]
        }
    }
}
</script>

<template>

    <footer>
        <section id="footer-navbar">
            <div class="container">
                <div class="nav-menu">
                    <div class="nav-links">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>characters</li>
                            <li>comics</li>
                            <li>movies</li>
                            <li>tv</li>
                            <li>games</li>
                            <li>collectibles</li>
                        </ul>
                    </div>

                    <div class="nav-links">
                        <h3>SHOP</h3>
                        <ul>
                            <li>characters</li>
                            <li>comics</li>
                        </ul>
                    </div>

                    <div class="nav-links">
                        <h3>DC</h3>
                        <ul>
                            <li>characters</li>
                            <li>comics</li>
                            <li>movies</li>
                            <li>tv</li>
                            <li>games</li>
                            <li>collectibles</li>
                            <li>videos</li>
                            <li>news</li>
                            <li>shop</li>
                        </ul>
                    </div>

                    <div class="nav-links">
                        <h3>SITES</h3>
                        <ul>
                            <li>characters</li>
                            <li>comics</li>
                            <li>movies</li>
                            <li>tv</li>

                        </ul>
                    </div>
                </div>

                <div class="big-dc-logo">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </section>

        <section id="sign-in-social">
            <div class="container" id="sign-in">
                <a href="#">SIGN-UP NOW!</a>
                <div id="social">
                    <h4>FOLLOW US</h4>
                    <div id="social-icons">
                        <img src="../assets/img/footer-facebook.png" alt="facebook">
                        <img src="../assets/img/footer-twitter.png" alt="twitter">
                        <img src="../assets/img/footer-youtube.png" alt="youtube">
                        <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                        <img src="../assets/img/footer-periscope.png" alt="periscope">
                    </div>

                </div>
            </div>
        </section>

    </footer>
</template>

<style lang="scss" scoped>
footer {
    height: 50vh;
    color: white;
}

#footer-navbar {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    padding: 30px;
    height: 80%;
    overflow: hidden;

    .container {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .nav-menu {
        height: 100%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        gap: 15px;

        .nav-links {
            margin-right: 20px;

            h3 {
                margin-bottom: 10px;
            }

            ul li {
                margin: 5px 0;
                font-size: 12px;
                color: gray;
            }
        }

    }
}

#sign-in-social {
    background-color: #303030;
    height: 20%;

    .container {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        z-index: 0;


        a {
            text-decoration: none;
            color: white;
            border: 2px solid var(--electric-blue);
            padding: 15px;
            font-weight: 300;
        }

        #social {
            display: flex;
            align-items: center;

            h4 {
                color: var(--electric-blue);
                margin-right: 20px;
            }

            #social-icons * {
                margin: 0 5px;
                cursor: pointer;
            }
        }
    }
}
</style>