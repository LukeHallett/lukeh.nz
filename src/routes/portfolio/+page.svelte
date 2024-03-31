<svelte:head>
    <title>Portfolio | Luke Hallett</title>
</svelte:head>

<script lang="ts">
    import bbch from '$lib/assets/bbch.jpg';
    import hybergg from '$lib/assets/hybergg.png';
</script>

<div class="bg-body-secondary mb-5">
    <div class="px-4 py-5 text-center">
        <h1 class="display-5 fw-bold text-body-emphasis">Portfolio</h1>

        <div class="col-lg-6 mx-auto">
            <p class="lead mb-4">Here are some of the projects I have worked on.</p>
        </div>
    </div>
</div>

<div class="bg-body-secondary mb-5">
    <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
            <div class="col-10 col-sm-8 col-lg-6">
                <img src={bbch} class="d-block mx-lg-auto img-fluid" alt="Bow Brickhill Community Hall Website" loading="lazy">
            </div>

            <div class="col-lg-6">
                <h2 class="fw-bold lh-1 mb-0">Bow Brickhill Community Hall</h2>

                <p class="lead">
                    Designing, developing, and maintaining a full-stack website and booking system for a local community hall.
                    Built using PHP, JavaScript, Laravel, MariaDB and Vite.
                </p>

                <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                    <a class="btn btn-primary btn-lg" href="https://bbcommunityhall.org.uk" target="_blank">Visit</a>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="bg-body-secondary mb-5">
    <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
            <div class="col-lg-6">
                <h2 class="fw-bold lh-1 mb-0">HyberGG Website</h2>

                <p class="lead">
                    The front-end site for the hosting company HyberGG, with dynamic pricing via the WHMCS API. Implemented CI/CD using GitLab and Cloudflare Pages. Built using JavaScript, HTML, CSS, and Svelte.
                </p>

                <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                    <a class="btn btn-primary btn-lg" href="https://dev.web.hyber.gg/" target="_blank">Visit</a>
                </div>
            </div>

            <div class="col-10 col-sm-8 col-lg-6">
                <img src={hybergg} class="d-block mx-lg-auto img-fluid" alt="HyberGG Website" loading="lazy">
            </div>
        </div>
    </div>
</div>

<!--<div class="bg-body-secondary mb-5">-->
<!--    <div class="container col-xxl-8 px-4 py-5">-->
<!--        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">-->
<!--            <div class="col-lg-6">-->
<!--                <h2 class="fw-bold lh-1 mb-0">Tower Resource Collection Game</h2>-->

<!--                <p class="lead">-->
<!--                    A game with a goal to maximise money gained by the end of a set amount of rounds by upgrading towers.-->
<!--                    Created as a software engineering project at University with a partner. Built using Java, JavaFX, and Gradle.-->
<!--                </p>-->

<!--                <div class="d-grid gap-2 d-md-flex justify-content-md-start">-->
<!--                    <a class="btn btn-primary btn-lg" href="#" target="_blank">Download</a>-->
<!--                    <a class="btn btn-outline-secondary btn-lg" href="#" target="_blank">Source Code</a>-->
<!--                </div>-->
<!--            </div>-->

<!--            <div class="col-10 col-sm-8 col-lg-6">-->
<!--                <img src={bbch} class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" loading="lazy">-->
<!--            </div>-->
<!--        </div>-->
<!--    </div>-->
<!--</div>-->
