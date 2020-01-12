<template>
    <div>
    <Form />
    <Header />
    <Menu />
    <Video />
    <Cards />
    <Projects />
    <Advantages />
    <Partners />
    <Articles />
    <News />
    <Contact />
    <Footer />
    <router-view />
    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Menu from '@/components/Menu.vue'
import Video from '@/components/Video.vue'
import Cards from '@/components/Cards.vue'
import Projects from '@/components/Projects.vue'
import Advantages from '@/components/Advantages.vue'
import Partners from '@/components/Partners.vue'
import Articles from '@/components/Articles.vue'
import News from '@/components/News.vue'
import Contact from '@/components/Contact.vue'
import Footer from '@/components/Footer.vue'
import Form from '@/components/Form.vue'
export default {
  name: 'app',
  components: {
    Header,
    Menu,
    Video,
    Cards,
    Projects,
    Advantages,
    Partners,
    Articles,
    News,
    Contact,
    Footer,
    Form
  }
}
</script>