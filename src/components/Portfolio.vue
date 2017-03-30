<template>
    <div>
        <div class="container">
            <div class="row">
                <h2>jasonZmuda.portfolio = {</h2>
            </div>
        </div>
        <!--<div class="row">
                <div class="col s12 m7">
                    <div class="card">
                        <div class="card-image">
                            <img src="images/sample-1.jpg">
                            <span class="card-title">Card Title</span>
                        </div>
                        <div class="card-content">
                            <p>I am a very simple card. I am good at containing small bits of information. I am convenient because
                                I require little markup to use effectively.</p>
                        </div>
                        <div class="card-action">
                            <a href="#">This is a link</a>
                        </div>
                    </div>
                </div>
            </div>-->
        <div class="container">
            <div class="row">
                <div class="col s3 offset-s2">
                    <div class="card small-box">
                        <div class="card-image waves-effect waves-block waves-light">
                            <img class="activator" :src="images.SteamImage">
                        </div>
                        <div class="card-content">
                            <span class="card-title activator grey-text text-darken-4">Multi Player<i class="material-icons right"></i></span>
                            <p><a href="https://jaime-lynn.github.io/multi-player/#/">view project</a></p>
                        </div>
                        <!--<div class="card-reveal">
                            <span class="card-title grey-text text-darken-4">Multi Player<i class="material-icons right">close</i></span>
                            <p>Here is some more information about this product that is only revealed once clicked on.</p>
                        </div>-->
                    </div>
                </div>

                <!--<div class="row">-->
                    <div class="col s3">
                        <div class="card small-box">
                            <div class="card-image waves-effect waves-block waves-light">
                                <img class="activator" :src="images.Github">
                            </div>
                            <div class="card-content">
                                <span class="card-title activator grey-text text-darken-4"><a href="https://github.com/zmudaj">My Github</a><i class="material-icons right"></i></span>
                                
                            </div>
                            <!--<div class="card-reveal">
                                <span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">close</i></span>
                                <p>Here is some more information about this product that is only revealed once clicked on.</p>
                            </div>-->
                        </div>
                    </div>
                <!--</div>-->

                <div class="col s3">
                        <div class="card small-box">
                            <div class="card-image waves-effect waves-block waves-light">
                                <img class="activator" :src="images.PlaceholderImage">
                            </div>
                            <div class="card-content">
                                <span class="card-title activator grey-text text-darken-4">Keepr App<i class="material-icons right"></i></span>
                                <p><a href="#">Coming Soon</a></p>
                            </div>
                            <!--<div class="card-reveal">
                                <span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">close</i></span>
                                <p>Here is some more information about this product that is only revealed once clicked on.</p>
                            </div>-->
                        </div>
                    </div>
                </div>

           
        </div>
        <div class="container">
            <div class="row">
        <h2> };</h2>
        </div>
        </div>
    </div>
</template>

<script>
    import SteamImage from "../assets/steamylanding.jpg"
    import PlaceholderImage from "../assets/placeholder.png"
    import Github from "../assets/github.png"
    export default {
        name: 'portfolio',
        data() {
            return {
                images: {
                    SteamImage: SteamImage,
                    PlaceholderImage: PlaceholderImage,
                    Github: Github
                }
            }
        }
    }

</script>

<style>
    .small-box {
        max-width: 200px;
    }
</style>