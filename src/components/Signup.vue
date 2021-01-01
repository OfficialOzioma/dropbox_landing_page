<template>
    <div id="signup">
        <div class="container-fluid">
            <div class="row">
                <div class="col col-8 bg-primary text-white" style="background: rgb(39,111,183);">
                    <div>
                        <h4 class="ml-4 p-2">Dropbox</h4>
                        <h1 class="ml-4"><span class="display-1 p-3 text-justify"><strong>Focus on the work that matters</strong></span></h1>
                        <h4 class="ml-4 mt-4 p-3 text-justify"><span>Dropbox is the world’s first smart workspace. We bring all your team’s content together while letting you use the tools you love. And we help cut through the clutter, surfacing what matters most.</span></h4>
                    </div>
                </div>
                <div class="col col-4"  :class="{ 'hide': !showsignup }">
                    <div class="signup_div p-3">
                        <h3 class="pl-2 pt-2 ml-5"><span>Sign up</span></h3><span class="pl-2 pt-0 ml-5">or&nbsp;<a href="https://www.dropbox.com/#">sign in to your account</a></span>
                        <div class="p-2 ml-4">
                            <form class="mt-4 ml-4">
                                <div class="form-group"><input class="form-control" type="text" placeholder="First name"></div>
                                <div class="form-group"><input class="form-control" type="text" placeholder="Last name"></div>
                                <div class="form-group"><input class="form-control" type="text" placeholder="Email"></div>
                                <div class="form-group"><input class="form-control" type="text" placeholder="Password"></div>
                                <div class="form-group">
                                    <div class="form-check"><input class="form-check-input" type="checkbox" id="formCheck-1"><label class="form-check-label" for="formCheck-1">I agree to the&nbsp;<a href="https://www.dropbox.com/terms">Dropbox Terms</a></label></div>
                                </div>
                                <div class="form-group"><button class="btn btn-primary btn-lg w-100" type="button">Sign up</button></div>
                                <div class="form-group"><button class="btn btn-lg w-100 p-3" style="border-style: solid;border-color: #cccfd2;font-size: 15px;"><i class="fa fa-google"></i>&nbsp; Sign up with google</button></div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div >
</template>

<script>
export default {
    name: "Signup"
}
</script>

