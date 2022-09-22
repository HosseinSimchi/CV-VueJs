<template>
    <div id="about">
        <div class="container content-lg">
            <div class="row">
                <div class="col-sm-3 sm-margin-b-30">
                    <div class="text-right sm-text-left">
                        <h2 class="margin-b-0">Intro</h2>
                        <p>What I am all about.</p>
                    </div>
                </div>
                <div class="col-sm-8 col-sm-offset-1">
                    <div class="margin-b-60">
                        <p>I'm Hossein Simchi, I have been working on web Full stack developer such as MERN, MEAN and MEVN stacks sicne 2021</p>
                    </div>

                    <!-- Progress Box -->
                    <div class="progress-box" v-for="(item,index) of skillsName" :key="item">
                        <h5>{{item}} <span class="color-heading pull-right">{{skillsPercents[index]}}%</span></h5>
                        <div class="progress">
                            <div class="progress-bar bg-color-base" role="progressbar" :data-width="skillsPercents[index]"></div>
                        </div>
                    </div>
                    <!-- End Progress Box -->
                </div>
            </div>
            <!--// end row -->
        </div>
    </div>
</template>

<script>
export default {
    name: 'aboutSite',
    data () {
        return {
            skillsName:['Angular JS', 'JavaSript', 'HTML5 & CSS', 'React JS', 'Vue JS', 'Python', 'Django', 'Git & GitHub'],
            skillsPercents : ['50','95','80','50','85','95','60','95']
        }
    }
}
</script>
