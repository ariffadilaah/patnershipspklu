<template>
  <div id="___layout">
    <div>
      <!-- ----NAVBAR 1------ -->
      <nav class="navbar navbar-expand-lg navbar-light bg-light px-5">
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                <img src="../assets/iconinformasi.png" alt="" width="15" />
                <font size="2" color="#838282"> Info Lainnya </font>
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Action</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <img
                  src="../assets/Icon_PLN_Mobile_Grey_Info Layanan@2x.png"
                  alt=""
                  width="15"
                />
                <font size="2" color="#838282"> Info Layanan </font></a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <img
                  src="../assets/Icon_PLN_Mobile_Grey_Promo@2x.png"
                  alt=""
                  width="15"
                />
                <font size="2" color="#838282"> Promo </font></a
              >
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <!-- -------NAVBAR------- -->
    <div>
      <nav class="navbar navbar-expand-lg navbar-light bg-transparent pl-5">
        <img class="logo" src="../assets/logoPLN.png" alt="" />
        <router-link class="nav-link active text-primary" to="/">
          <img
            class="img-fluid"
            src="../assets/browser@2x.png"
            alt=""
            width="10"
          />
          Home</router-link
        >
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                Permohonan
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Action</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>
              </div>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                Simulasi
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Action</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Renawable Energy Certificate</a>
            </li>

            <li class="nav-item">
              <router-link to="/patnership" class="nav-link"
                >Patnership SPKLU</router-link
              >
            </li>
          </ul>
          <!-- LOGIN AND REGISTER -->
          <li class="list-inline-item tooltip-hover">
            <a data-toggle="modal" href="#">
              <font size="2" color="#555">
                <b>Masuk | </b>
              </font>
            </a>
          </li>
          <li class="list-inline-item tooltip-hover">
            <a data-toggle="modal" href="#">
              <font size="2" color="#40caff">
                <b>Daftar </b>
              </font>
            </a>
          </li>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.navbar-expand-lg .navbar-nav .nav-link {
  padding-right: 0.5rem;
  padding-left: 0.5rem;
}
.banner {
  width: 100%;
}
.info {
  width: 15px;
}
.img-fluid,
.img-thumbnail {
  max-width: 100%;
  height: auto;
}
.logo {
  width: 5%;
}
.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
.justify-content-center {
  justify-content: center !important;
}
.counter-wrap {
  background: #fff;
  width: 80%;
  position: relative;
  bottom: -60px;
  padding: 20px;
  /* padding-top: 20px;
  padding-right: 0px;
  padding-bottom: 20px;
  padding-left: 0px; */
  border-radius: 10px;
  box-shadow: 0 3px 10px rgb(0 0 0 / 12%);
  flex-wrap: wrap;
  grid-auto-flow: dense;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
}
.list-inline,
.list-unstyled {
  list-style: none;
  list-style-position: initial;
  list-style-image: initial;
  list-style-type: none;
}
.counter-wrap li {
  display: flex;
  flex-direction: column;
  overflow: hidden;
  overflow-x: hidden;
  overflow-y: hidden;
  text-align: center;
  border-right: 0 solid #ebebeb;
  border-right-width: 0px;
  border-right-style: solid;
  border-right-color: rgb(235, 235, 235);
  margin: 0 !important;
  margin-top: 0px !important;
  margin-right: 0px !important;
  margin-bottom: 0px !important;
  margin-left: 0px !important;
}
.features-box {
  position: relative;
  display: block;
}
.p-4 {
  padding: 1.5rem !important;
  padding-top: 1.5rem !important;
  padding-right: 1.5rem !important;
  padding-bottom: 1.5rem !important;
  padding-left: 1.5rem !important;
}
.features-box-icon {
  display: table-cell;
  vertical-align: top;
}
img {
  vertical-align: middle;
  border-style: none;
  border-top-style: none;
  border-right-style: none;
  border-bottom-style: none;
  border-left-style: none;
}
.features-box-content {
  display: table-cell;
  padding-left: 20px;
}
a {
  color: #1890ff;
  text-decoration: none;
  background-color: transparent;
  outline: 0;
  cursor: pointer;
  transition: color 0.3s;
}
h5 {
  font-size: 1.25em;
}
.list-inline-item:not(:last-child) {
  margin-right: 0.5rem;
}
.list-inline-item {
  display: inline-block;
}
.tooltip-hover {
  position: relative;
}
.tooltip-hover a {
  display: block;
}
b,
strong {
  font-weight: bolder;
}
.ptb-100 {
  padding: 100px 0;
}
.mt-5,
.my-5 {
  margin-top: 3rem !important;
}
.mt-4,
.my-4 {
  margin-top: 1.5rem !important;
}
.mb-3,
.my-3 {
  margin-bottom: 1rem !important;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  margin-top: 0;
  margin-bottom: 0.5em;
  color: rgba(0, 0, 0, 0.85);
  font-weight: 500;
  margin: 0 0 1rem;
  font-family: Comfortaa, sans-serif;
}
h2 {
  font-size: 2.441em;
}
.lead {
  font-size: 1.25rem;
  font-weight: 300;
}
p {
  margin-top: 0;
  margin-bottom: 1em;
}
.promo-info {
  padding: 30px;
}
.btn {
  text-align: center;
  vertical-align: middle;
  cursor: pointer;
  user-select: none;
  background-color: transparent;
  line-height: 1.5;
  border-radius: 25rem;
}
.btn-outline-primary {
  position: relative;
  display: inline-block;
  color: #0099f6;
  border: 1px solid #0099f6;
}
.primary-outline,
.btn-primary-outline,
.btn-primary-solid,
.solid-btn {
  padding: 0.75rem 1.85rem;
  font-family: Comfortaa, sans-serif;
  font-size: 14px;
  font-weight: 600;
  transition: all 0.25s ease-in-out;
}
.col-lg-4 {
  flex: 0 0 33.333333%;
  max-width: 33.333333%;
}
.img-fluid,
.img-thumbnail {
  max-width: 100%;
  height: auto;
}
.nav-link {
  display: block;
  padding: 0.5rem 1rem;
}
.col {
  flex-basis: 0;
  flex-grow: 1;
  max-width: 100%;
}
.text-lg-right {
  text-align: right !important;
}
</style>