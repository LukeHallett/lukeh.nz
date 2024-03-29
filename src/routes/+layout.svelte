<script lang="ts">
    // import { onMount } from "svelte";

    import '../app.scss';

    // onMount(async () => {
    //     window.bootstrap = await import('bootstrap/dist/js/bootstrap.bundle.min.js');
    // });
</script>

<nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container">
        <a class="navbar-brand" href="/">Luke Hallett</a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar" aria-controls="navbar" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbar">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="/">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="/portfolio">Portfolio</a></li>
            </ul>
        </div>
    </div>
</nav>

<slot></slot>

<div class="bg-body-secondary mt-auto">
    <div class="container">
        <footer class="d-flex flex-wrap justify-content-between align-items-center py-3">
            <div class="col-md-4 d-flex align-items-center">
                <span class="mb-3 mb-md-0 text-body-secondary">&copy; Luke Hallett</span>
            </div>

<!--            <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">-->
<!--                <li class="ms-3"><a class="text-body-secondary" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#twitter"></use></svg></a></li>-->
<!--                <li class="ms-3"><a class="text-body-secondary" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#instagram"></use></svg></a></li>-->
<!--                <li class="ms-3"><a class="text-body-secondary" href="#"><svg class="bi" width="24" height="24"><use xlink:href="#facebook"></use></svg></a></li>-->
<!--            </ul>-->
        </footer>
    </div>
</div>