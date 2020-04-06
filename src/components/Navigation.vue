<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark static-top">
            <button class="navbar-toggler" type="button" data-toggle="collapse"
              data-target="#navbarTogglerDemo03"
              aria-controls="navbarTogglerDemo03"
              aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand" href="#"><img src="../assets/img/Logo.webp" alt="Logo" width="80px">
        </a>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
                <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
                <li class="nav-item active">
                    <a class="nav-link" href="#">
                      Home
                    <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                <a class="nav-link disabled" href="#">Disabled</a>
                </li>
                </ul>
            </div>
        </nav>
    </div>
</template>
<script>
export default {
  name: 'Header'
}
</script>








