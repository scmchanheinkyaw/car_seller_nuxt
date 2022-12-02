<template>
  <div>
    <section class="header-img w-100 position-relative flex pb-5">
      <div class="position-absolute w-100 h-100 text-center top-50">
        <h1 class="text-white fs-3">We make finding the right car simple.</h1>
      </div>
      <form action="" class="position-absolute w-100 search-form position-relative" autocomplete="off">
          <input type="text" name="search" placeholder="What car are you looking for? (Make/Model)" class="border border-primary w-50 p-2 rounded-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-search position-absolute text-info" viewBox="0 0 20 20">
            <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
            </svg>
        </form>
      <!-- Background image -->
      <img src="~/assets/header-img.png" alt="" class="w-100 h-100"/>
    </section>
    <section class="mt-3 container">
      <div class="flex text-center fs-3 fw-bold mb-5">LATEST POST</div>
      <div class="row">
        <div class="col-md-3">
          <Nuxt-Link to="#" class="card-custom">
            <div class="card rounded-2" style="width: 20rem">
              <div class="img-card">
                <img
                  src="../assets/logo.png"
                  class="card-img-top h-100 w-100"
                />
              </div>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <span class="card-text">Some quick example</span>
                <div class="flex p-2 mt-3 bg-light">
                  <div class="w-50 float-start">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-speedometer2"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M8 4a.5.5 0 0 1 .5.5V6a.5.5 0 0 1-1 0V4.5A.5.5 0 0 1 8 4zM3.732 5.732a.5.5 0 0 1 .707 0l.915.914a.5.5 0 1 1-.708.708l-.914-.915a.5.5 0 0 1 0-.707zM2 10a.5.5 0 0 1 .5-.5h1.586a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 10zm9.5 0a.5.5 0 0 1 .5-.5h1.5a.5.5 0 0 1 0 1H12a.5.5 0 0 1-.5-.5zm.754-4.246a.389.389 0 0 0-.527-.02L7.547 9.31a.91.91 0 1 0 1.302 1.258l3.434-4.297a.389.389 0 0 0-.029-.518z"
                      />
                      <path
                        fill-rule="evenodd"
                        d="M0 10a8 8 0 1 1 15.547 2.661c-.442 1.253-1.845 1.602-2.932 1.25C11.309 13.488 9.475 13 8 13c-1.474 0-3.31.488-4.615.911-1.087.352-2.49.003-2.932-1.25A7.988 7.988 0 0 1 0 10zm8-7a7 7 0 0 0-6.603 9.329c.203.575.923.876 1.68.63C4.397 12.533 6.358 12 8 12s3.604.532 4.923.96c.757.245 1.477-.056 1.68-.631A7 7 0 0 0 8 3z"
                      />
                    </svg>
                    600km
                  </div>
                  <div class="w-50 float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-fuel-pump"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3 2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5v-5Z"
                      />
                      <path
                        d="M1 2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 2 2v.5a.5.5 0 0 0 1 0V8h-.5a.5.5 0 0 1-.5-.5V4.375a.5.5 0 0 1 .5-.5h1.495c-.011-.476-.053-.894-.201-1.222a.97.97 0 0 0-.394-.458c-.184-.11-.464-.195-.9-.195a.5.5 0 0 1 0-1c.564 0 1.034.11 1.412.336.383.228.634.551.794.907.295.655.294 1.465.294 2.081v3.175a.5.5 0 0 1-.5.501H15v4.5a1.5 1.5 0 0 1-3 0V12a1 1 0 0 0-1-1v4h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1V2Zm9 0a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v13h8V2Z"
                      />
                    </svg>
                    CNG
                  </div>
                  <div class="w-100 flex calendar-icon">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-calendar"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"
                      />
                    </svg>
                    Dec 2, 2022
                    <span class="text-dark">(4 hours ago)</span>
                  </div>
                </div>
              </div>
              <div class="p-3">
                <div class="border-top border-1 py-3">
                  <div class="float-start">
                    <Nuxt-Link to="#" class="text-dark text-decoration-none">
                      <img
                        src="../assets/logo.png"
                        alt=""
                        class="profile-img"
                      />
                      <span>Chan Hein Kyaw</span>
                    </Nuxt-Link>
                  </div>
                  <div class="float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-heart"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"
                      />
                    </svg>
                    2
                  </div>
                </div>
              </div>
            </div>
          </Nuxt-Link>
        </div>

        <div class="col-md-3">
          <Nuxt-Link to="#" class="card-custom">
            <div class="card rounded-2" style="width: 20rem">
              <div class="img-card">
                <img
                  src="../assets/logo.png"
                  class="card-img-top h-100 w-100"
                />
              </div>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <span class="card-text">Some quick example</span>
                <div class="flex p-2 mt-3 bg-light">
                  <div class="w-50 float-start">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-speedometer2"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M8 4a.5.5 0 0 1 .5.5V6a.5.5 0 0 1-1 0V4.5A.5.5 0 0 1 8 4zM3.732 5.732a.5.5 0 0 1 .707 0l.915.914a.5.5 0 1 1-.708.708l-.914-.915a.5.5 0 0 1 0-.707zM2 10a.5.5 0 0 1 .5-.5h1.586a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 10zm9.5 0a.5.5 0 0 1 .5-.5h1.5a.5.5 0 0 1 0 1H12a.5.5 0 0 1-.5-.5zm.754-4.246a.389.389 0 0 0-.527-.02L7.547 9.31a.91.91 0 1 0 1.302 1.258l3.434-4.297a.389.389 0 0 0-.029-.518z"
                      />
                      <path
                        fill-rule="evenodd"
                        d="M0 10a8 8 0 1 1 15.547 2.661c-.442 1.253-1.845 1.602-2.932 1.25C11.309 13.488 9.475 13 8 13c-1.474 0-3.31.488-4.615.911-1.087.352-2.49.003-2.932-1.25A7.988 7.988 0 0 1 0 10zm8-7a7 7 0 0 0-6.603 9.329c.203.575.923.876 1.68.63C4.397 12.533 6.358 12 8 12s3.604.532 4.923.96c.757.245 1.477-.056 1.68-.631A7 7 0 0 0 8 3z"
                      />
                    </svg>
                    600km
                  </div>
                  <div class="w-50 float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-fuel-pump"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3 2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5v-5Z"
                      />
                      <path
                        d="M1 2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 2 2v.5a.5.5 0 0 0 1 0V8h-.5a.5.5 0 0 1-.5-.5V4.375a.5.5 0 0 1 .5-.5h1.495c-.011-.476-.053-.894-.201-1.222a.97.97 0 0 0-.394-.458c-.184-.11-.464-.195-.9-.195a.5.5 0 0 1 0-1c.564 0 1.034.11 1.412.336.383.228.634.551.794.907.295.655.294 1.465.294 2.081v3.175a.5.5 0 0 1-.5.501H15v4.5a1.5 1.5 0 0 1-3 0V12a1 1 0 0 0-1-1v4h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1V2Zm9 0a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v13h8V2Z"
                      />
                    </svg>
                    CNG
                  </div>
                  <div class="w-100 flex calendar-icon">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-calendar"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"
                      />
                    </svg>
                    Dec 2, 2022
                    <span class="text-dark">(4 hours ago)</span>
                  </div>
                </div>
              </div>
              <div class="p-3">
                <div class="border-top border-1 py-3">
                  <div class="float-start">
                    <Nuxt-Link to="#" class="text-dark text-decoration-none">
                      <img
                        src="../assets/logo.png"
                        alt=""
                        class="profile-img"
                      />
                      <span>Chan Hein Kyaw</span>
                    </Nuxt-Link>
                  </div>
                  <div class="float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-heart"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"
                      />
                    </svg>
                    2
                  </div>
                </div>
              </div>
            </div>
          </Nuxt-Link>
        </div>

        <div class="col-md-3">
          <Nuxt-Link to="#" class="card-custom">
            <div class="card rounded-2" style="width: 20rem">
              <div class="img-card">
                <img
                  src="../assets/logo.png"
                  class="card-img-top h-100 w-100"
                />
              </div>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <span class="card-text">Some quick example</span>
                <div class="flex p-2 mt-3 bg-light">
                  <div class="w-50 float-start">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-speedometer2"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M8 4a.5.5 0 0 1 .5.5V6a.5.5 0 0 1-1 0V4.5A.5.5 0 0 1 8 4zM3.732 5.732a.5.5 0 0 1 .707 0l.915.914a.5.5 0 1 1-.708.708l-.914-.915a.5.5 0 0 1 0-.707zM2 10a.5.5 0 0 1 .5-.5h1.586a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 10zm9.5 0a.5.5 0 0 1 .5-.5h1.5a.5.5 0 0 1 0 1H12a.5.5 0 0 1-.5-.5zm.754-4.246a.389.389 0 0 0-.527-.02L7.547 9.31a.91.91 0 1 0 1.302 1.258l3.434-4.297a.389.389 0 0 0-.029-.518z"
                      />
                      <path
                        fill-rule="evenodd"
                        d="M0 10a8 8 0 1 1 15.547 2.661c-.442 1.253-1.845 1.602-2.932 1.25C11.309 13.488 9.475 13 8 13c-1.474 0-3.31.488-4.615.911-1.087.352-2.49.003-2.932-1.25A7.988 7.988 0 0 1 0 10zm8-7a7 7 0 0 0-6.603 9.329c.203.575.923.876 1.68.63C4.397 12.533 6.358 12 8 12s3.604.532 4.923.96c.757.245 1.477-.056 1.68-.631A7 7 0 0 0 8 3z"
                      />
                    </svg>
                    600km
                  </div>
                  <div class="w-50 float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-fuel-pump"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3 2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5v-5Z"
                      />
                      <path
                        d="M1 2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 2 2v.5a.5.5 0 0 0 1 0V8h-.5a.5.5 0 0 1-.5-.5V4.375a.5.5 0 0 1 .5-.5h1.495c-.011-.476-.053-.894-.201-1.222a.97.97 0 0 0-.394-.458c-.184-.11-.464-.195-.9-.195a.5.5 0 0 1 0-1c.564 0 1.034.11 1.412.336.383.228.634.551.794.907.295.655.294 1.465.294 2.081v3.175a.5.5 0 0 1-.5.501H15v4.5a1.5 1.5 0 0 1-3 0V12a1 1 0 0 0-1-1v4h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1V2Zm9 0a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v13h8V2Z"
                      />
                    </svg>
                    CNG
                  </div>
                  <div class="w-100 flex calendar-icon">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-calendar"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"
                      />
                    </svg>
                    Dec 2, 2022
                    <span class="text-dark">(4 hours ago)</span>
                  </div>
                </div>
              </div>
              <div class="p-3">
                <div class="border-top border-1 py-3">
                  <div class="float-start">
                    <Nuxt-Link to="#" class="text-dark text-decoration-none">
                      <img
                        src="../assets/logo.png"
                        alt=""
                        class="profile-img"
                      />
                      <span>Chan Hein Kyaw</span>
                    </Nuxt-Link>
                  </div>
                  <div class="float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-heart"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"
                      />
                    </svg>
                    2
                  </div>
                </div>
              </div>
            </div>
          </Nuxt-Link>
        </div>
        <div class="col-md-3">
          <Nuxt-Link to="#" class="card-custom">
            <div class="card rounded-2" style="width: 20rem">
              <div class="img-card">
                <img
                  src="../assets/logo.png"
                  class="card-img-top h-100 w-100"
                />
              </div>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <span class="card-text">Some quick example</span>
                <div class="flex p-2 mt-3 bg-light">
                  <div class="w-50 float-start">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-speedometer2"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M8 4a.5.5 0 0 1 .5.5V6a.5.5 0 0 1-1 0V4.5A.5.5 0 0 1 8 4zM3.732 5.732a.5.5 0 0 1 .707 0l.915.914a.5.5 0 1 1-.708.708l-.914-.915a.5.5 0 0 1 0-.707zM2 10a.5.5 0 0 1 .5-.5h1.586a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 10zm9.5 0a.5.5 0 0 1 .5-.5h1.5a.5.5 0 0 1 0 1H12a.5.5 0 0 1-.5-.5zm.754-4.246a.389.389 0 0 0-.527-.02L7.547 9.31a.91.91 0 1 0 1.302 1.258l3.434-4.297a.389.389 0 0 0-.029-.518z"
                      />
                      <path
                        fill-rule="evenodd"
                        d="M0 10a8 8 0 1 1 15.547 2.661c-.442 1.253-1.845 1.602-2.932 1.25C11.309 13.488 9.475 13 8 13c-1.474 0-3.31.488-4.615.911-1.087.352-2.49.003-2.932-1.25A7.988 7.988 0 0 1 0 10zm8-7a7 7 0 0 0-6.603 9.329c.203.575.923.876 1.68.63C4.397 12.533 6.358 12 8 12s3.604.532 4.923.96c.757.245 1.477-.056 1.68-.631A7 7 0 0 0 8 3z"
                      />
                    </svg>
                    600km
                  </div>
                  <div class="w-50 float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-fuel-pump"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3 2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5v-5Z"
                      />
                      <path
                        d="M1 2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 2 2v.5a.5.5 0 0 0 1 0V8h-.5a.5.5 0 0 1-.5-.5V4.375a.5.5 0 0 1 .5-.5h1.495c-.011-.476-.053-.894-.201-1.222a.97.97 0 0 0-.394-.458c-.184-.11-.464-.195-.9-.195a.5.5 0 0 1 0-1c.564 0 1.034.11 1.412.336.383.228.634.551.794.907.295.655.294 1.465.294 2.081v3.175a.5.5 0 0 1-.5.501H15v4.5a1.5 1.5 0 0 1-3 0V12a1 1 0 0 0-1-1v4h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1V2Zm9 0a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v13h8V2Z"
                      />
                    </svg>
                    CNG
                  </div>
                  <div class="w-100 flex calendar-icon">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      fill="currentColor"
                      class="bi bi-calendar"
                      viewBox="0 0 20 20"
                    >
                      <path
                        d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"
                      />
                    </svg>
                    Dec 2, 2022
                    <span class="text-dark">(4 hours ago)</span>
                  </div>
                </div>
              </div>
              <div class="p-3">
                <div class="border-top border-1 py-3">
                  <div class="float-start">
                    <Nuxt-Link to="#" class="text-dark text-decoration-none">
                      <img
                        src="../assets/logo.png"
                        alt=""
                        class="profile-img"
                      />
                      <span>Chan Hein Kyaw</span>
                    </Nuxt-Link>
                  </div>
                  <div class="float-end">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-heart"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="m8 2.748-.717-.737C5.6.281 2.514.878 1.4 3.053c-.523 1.023-.641 2.5.314 4.385.92 1.815 2.834 3.989 6.286 6.357 3.452-2.368 5.365-4.542 6.286-6.357.955-1.886.838-3.362.314-4.385C13.486.878 10.4.28 8.717 2.01L8 2.748zM8 15C-7.333 4.868 3.279-3.04 7.824 1.143c.06.055.119.112.176.171a3.12 3.12 0 0 1 .176-.17C12.72-3.042 23.333 4.867 8 15z"
                      />
                    </svg>
                    2
                  </div>
                </div>
              </div>
            </div>
          </Nuxt-Link>
        </div>
      </div>
    </section>

    <section class="w-100 d-flex justify-content-center my-5">
      <nav aria-label="Page navigation example">
        <ul class="pagination">
          <li class="page-item">
            <a class="page-link" href="#" aria-label="Previous">
              <span aria-hidden="true">&laquo;</span>
              <span class="sr-only"></span>
            </a>
          </li>
          <li class="page-item"><a class="page-link" href="#">1</a></li>
          <li class="page-item"><a class="page-link" href="#">2</a></li>
          <li class="page-item"><a class="page-link" href="#">3</a></li>
          <li class="page-item">
            <a class="page-link" href="#" aria-label="Next">
              <span aria-hidden="true">&raquo;</span>
              <span class="sr-only"></span>
            </a>
          </li>
        </ul>
      </nav>
    </section>
  </div>
</template>

<script></script>

<style scoped>
.calendar-icon {
  padding-top: 35px;
}

.profile-img {
  width: 10%;
}

.img-card {
  overflow: hidden;
  height: 200px;
}

.card-img-top {
  object-fit: cover;
}

.card-custom {
  color: inherit;
  text-decoration: inherit;
}


.header-img {
  overflow: hidden;
  height: 400px;
}

.header-img>img{
    object-fit: cover;
}

.search-form{
    top: 82%;
    left: 22%;
}

.bi-search{
    left: 48%;
    top: 28%;
}

input:focus{
    outline: none;
}
</style>

<script>
    export default{
        layout: "home"
    }
</script>
