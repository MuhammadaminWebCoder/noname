<template>
      <div class="Navbar">
            <div class="containers d-flex justify-content-between align-items-center">
                  <router-link to="/"><img src="./icons/logo.svg"></router-link>
                  <ul class="d-flex align-items-center">
                        <li class="list-type mx-5"><router-link class="link span" to="/aboutUs">About Us</router-link></li>
                        <li class="list-type mx-5"><router-link class="link span" to="/ourService">Our Service</router-link></li>
                        <li class="list-type mx-5"><router-link class="link span" to="/theTeam">The team</router-link></li>
                        <li class="list-type mx-5"><router-link class="link span" to="/portfolio">Portfolio</router-link></li>
                        <li class="list-type ms-5"><router-link class="btn bg-blu b-circle shadow-btn px-5 py-2 link" to="/aboutUs">Get in touch</router-link></li>
                  </ul>
            </div>
      </div>
</template>