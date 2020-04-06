<template>
    <div>
        <section class="section">
            <div class="container-fliud text-center">
                <img alt="Vue logo" class="rounded-circle" src="../assets/img/profile.jpg" width="250px">
                <h1>Web Developer</h1>
                <p>This is a fun project I built in Vue and Bootstrap
                </p>
                <button type="button" class="btn btn-primary btn-lg">
                  Contact
                </button>
            </div>
        </section>
        <section class="portfolio text-center">
            <h1>Portfolio</h1>
            <p>These are suppose to be sample projects</p>
            <div class="container">
                <div class="row">
                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head text-center">
                                    <img alt="Vue logo"
                                      class="rounded-circle img-custome"
                                      src="../assets/img/profile.jpg">
                                    <h2>web project</h2>
                                </div>
                                <hr>
                                <div class="card-body">
                                    <p>
                                        Donec sed odio dui.
                                  Etiam porta sem malesuada magna mollis euismod.
                          Nullam id dolor id nibh ultricies vehicula ut id elit.
                                Morbi leo risus, porta ac consectetur ac,
                            vestibulum at eros. Praesent commodo cursus magna.
                                    </p>
                          <button type="button" class="btn btn-outline-primary">
                            More
                            </button>
                                </div>
                            </div>
                            <br>
                    </div>
                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head text-center">
                                    <img alt="Vue logo" class="rounded-circle img-custome"  src="../assets/img/profile.jpg">
                                    <h2>web project</h2>
                                </div>
                                <hr>
                                <div class="card-body">
                                    <p>
                                        Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.
                                        Nullam id dolor id nibh ultricies vehicula ut id elit.
                                        Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.
                                    </p>
                                    <button type="button" class="btn btn-outline-primary">More</button>
                                </div>
                            </div>
                        <br>
                    </div>
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head text-center">
                                <img alt="Vue logo" class="rounded-circle img-custome" src="../assets/img/profile.jpg">
                                <h2>web project</h2>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p>
                                    Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.
                                    Nullam id dolor id nibh ultricies vehicula ut id elit.
                                    Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.
                                </p>
                                <button type="button" class="btn btn-outline-primary">More</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>
<style lang="css" scoped>
    .section{
        padding-top: 10%;
        padding-bottom: 10%;
    }
    .portfolio {
        background-color: #34345238;
        padding-top: 8%;
        padding-bottom: 15%;
        /* padding:15% */
    }
    .img-custome {
        width: 140px;
        height: 140px;
        margin-top: 15px;
    }
</style>