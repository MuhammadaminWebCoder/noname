<template>
      <navbar/>
      <content/>
      <main>
            <section>
            <company/>
            </section>
            <section>
            <yourTeam/>
            </section>
            <section>
            <bussinesHelp/>
            </section>
            <section>
            <partner/>
            </section>
            <section>
            <mobileCarousel/>
            </section>
            <section>
            <price/>
            </section>
            <section>
            <future/> 
            </section>
            <section>
            <clientHappy/>
            </section>
            <section>
            <subscribeSearch/>
            </section>
      </main>
      <Footer/>
</template>

<script>
import navbar from '../components/Navbar.vue'
import content from '../components/Content.vue'
import Footer from '../components/Footer.vue'
import company from '../components/main/Company.vue'
import yourTeam from '../components/main/YourTeam.vue'
import bussinesHelp from '../components/main/BussinesHelp.vue'
import partner from '../components/main/Partner.vue'
import mobileCarousel from '../components/main/MobileCarousel.vue'
import price from '../components/main/Price.vue'
import future from '../components/main/Future.vue'
import clientHappy from '../components/main/ClientHappy.vue'
import subscribeSearch from '../components/main/SubscribeSearch.vue'

export default{
      components:{
            navbar,
            content,
            Footer,
            company,
            yourTeam,
            bussinesHelp,
            partner,
            mobileCarousel,
            price,
            future,
            clientHappy,
            subscribeSearch
      }
}
</script>