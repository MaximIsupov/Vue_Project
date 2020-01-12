<template>
  <div>
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
export default {
  name: 'app',
    data(){
        return{
            todos: [
                {id:1, title:'Купить хлеб', completed:false},
                {id:2, title:'Купить масло', completed:false},
                {id:3, title:'Купить воды', completed:false},
            ]
        }
    },
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
    Footer
  }
}
</script>


