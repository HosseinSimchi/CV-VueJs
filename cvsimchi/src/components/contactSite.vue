<template>
    <div id="contact">
        <div class="bg-color-sky-light">
            <div class="container content-lg">
                <div class="row">
                    <div class="col-sm-3 sm-margin-b-30">
                        <div class="text-right sm-text-left">
                            <h2 class="margin-b-0">Contacts</h2>
                        </div>
                    </div>
                    <div class="col-sm-8 col-sm-offset-1">
                        <div class="row">
                            <div class="col-md-3 col-xs-6 md-margin-b-30">
                                <h5>Location</h5>
                                <a href="#">{{Location}}</a>
                            </div>
                            <div class="col-md-3 col-xs-6 md-margin-b-30">
                                <h5>Phone</h5>
                                <a href="#">{{Phone}}</a>
                            </div>
                            <div class="col-md-3 col-xs-6">
                                <h5>Email</h5>
                                <a href="mailto:#">{{Email}}</a>
                            </div>
                        </div>
                    </div>
                </div>
                <!--// end row -->
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'contactSite',
    data () {
        return {
            Phone : "+98 935 199 6829",
            Email : "hsimchi74@gmail.com",
            Location : "Iran, Tehran"
        }
    }
}
</script>
