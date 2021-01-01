<template>
    <div id="about">
        <div class="container-fluid bg-primary text-white">
            <h1 class="p-5"><strong>File storage and sharing are <br /> just the beginning</strong><br></h1>
            <div class="row">
                <div class="col col-6">
                    <div>
                        <div id="features_div_1" class="features_div mb-4" @click="changepicture('img1')">
                            <h3 class="ml-5 pl-3"><strong>Be organized</strong></h3>
                            <h6 class="ml-5 pl-3">Bring traditional files, cloud content, Dropbox Paper docs, and web shortcuts together in one place—and work the way that works for you.</h6>
                        </div>
                        <div id="features_div_2" class="features_div mb-4" @click="changepicture('img2')">
                            <h3 class="ml-5 pl-3"><strong>Stay focused</strong></h3>
                            <h6 class="ml-5 pl-3">Personalized suggestions give you files and folders when you need them so you spend less time searching.</h6>
                        </div>
                        <div id="features_div_3" class="features_div mb-4 pb-4" @click="changepicture('img3')">
                            <h3 class="ml-5 pl-3"><strong>Get in sync</strong></h3>
                            <h6 class="ml-5 pl-3">Coordinate with your team and push projects forward with the tools you use every day—all within Dropbox.</h6>
                        </div>
                    </div>
                </div>
                <div class="col col-6">
                    <div class="feature_img mr-5">
                        <img src="assets/img/img1.png" id="img" >
                    </div>
                </div>
            </div>
            
            <hr class="bg-white">
            <div>
                <div class="row">
                    <div class="col col-7">
                        <div>
                            <h1 class="p-5 m-5"><strong>Learn more about the benefits of Dropbox</strong></h1>
                        </div>
                    </div>
                    <div class="col col-5">
                        <div class="p-5 m-5"><button class="btn btn-lg w-75" type="button" style="background: #f9f6f6;">See features</button></div>
                    </div>
                </div>
            </div>
        </div>
    </div >
</template>

<script>
export default {
    name: "Features",
    methods : {
       changepicture(id) {
           let img = document.getElementById('img')
           img.src ='assets/img/' + id +'.png'
       }
    }
}
</script>