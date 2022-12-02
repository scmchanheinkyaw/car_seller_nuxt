<template>
  <div>
    <div class="container-fluid navbar-light bg-light">
      <nav class="navbar navbar-expand-lg navbar-light bg-light container">
        <div class="container-fluid">
          <Nuxt-Link to="/">
            <img src="~/assets/logo.png" alt="" class="w-50" />
          </Nuxt-Link>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item dropdown">
                <Nuxt-Link
                  class="nav-link dropdown-toggle"
                  to="#"
                  id="navbarDropdown"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Language
                </Nuxt-Link>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li>
                    <Nuxt-Link to="/" class="dropdown-item" href="#"
                      >English</Nuxt-Link
                    >
                  </li>
                  <li>
                    <Nuxt-Link to="/" class="dropdown-item" href="#"
                      >Myanmar</Nuxt-Link
                    >
                  </li>
                </ul>
              </li>
              <li class="nav-item">
                <Nuxt-Link
                  class="nav-link active btn btn-info text-white mx-2 py-2 px-3"
                  aria-current="page"
                  to="/login"
                  >Login</Nuxt-Link
                >
              </li>
              <li class="nav-item">
                <Nuxt-Link
                  class="nav-link active btn btn-info text-white py-2 px-3"
                  aria-current="page"
                  to="/register"
                  >Register</Nuxt-Link
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
    <Nuxt />
  </div>
</template>

<script></script>
