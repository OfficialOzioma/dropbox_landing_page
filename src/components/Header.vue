<template>
    <div id="header">
        <nav class="navbar navbar-light navbar-expand-md navigation-clean">
        <div class="container"><i class="fa fa-dropbox"></i><a class="navbar-brand" href="#">Dropbox</a>
            <ul class="nav navbar-nav">
                <li class="nav-item"><a class="nav-link active" href="#">Why Dropbox?</a></li>
                <li class="nav-item"><a class="nav-link active" href="#">Features</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Plans &amp; Pricing</a></li>
            </ul>
            <div class="collapse navbar-collapse" id="navcol-1">
                <nav class="navbar navbar-light navbar-expand-md">
                    <div class="container-fluid"><button data-toggle="collapse" data-target="#navcol-1" class="navbar-toggler"><span class="sr-only">Toggle navigation</span><span class="navbar-toggler-icon"></span></button>
                        <div class="collapse navbar-collapse" id="navcol-2"></div>
                    </div>
                </nav>
                <ul class="nav navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link active" href="#">Support</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contacts sales</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">sign in</a></li>
                    <li class="nav-item"><button class="btn btn-primary" type="button">Get Started</button></li>
                </ul>
            </div>
        </div>
    </nav>
    </div>
</template>

<script>
    export default {
      name: "Header"  
    }
</script>