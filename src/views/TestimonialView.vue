
<template lang="">

<h1 class="ml1">
        <span class="text-wrapper">
          <span class="line line1"></span>
          <span class="letters">TESTIMONIALS</span>
          <span class="line line2"></span>
        </span>
      </h1><br>


<testimonial v-for="testi in testimonials" :key="testi.id" :id="testi.id" :image="testi.image" :person="testi.Person" :words="testi.words"/>

</template>
<script>
import testimonial from '@/components/testimonial.vue';

export default {
  name: 'HomeView',
  components: {
    testimonial
  },
  data() {
        return {
            testimonials: JSON.parse(localStorage.getItem('testimonials')) || [
                {
                    id: 0,
                    image: 'https://i.postimg.cc/j2DQRh9d/Screenshot-2022-11-04-142528.png',
                    Person: 'John-Bruce Noad',
                    words: 'The first thing I noticed about Tyvon, when working with him, his tenacity. When faced with a problem he will stop at nothing until he has found the solution! His creativity is clearly displayed in his web designs and he is always willing to help others. I wish him nothing but the best in his future endeavours',
                },
                {
                    id: 1,
                    image: 'https://i.postimg.cc/CMRQhCbq/Screenshot-2022-11-04-143454.png',
                    Person: 'Deno Rautenbach',
                    words: 'Tyvon is soft-spoken with roaring creativeness. Always fun to be around and a genius of course, because I can always depend on him for help on a problem I would have struggled with for ages. Hes got impeccable music taste and an eye for art.',
                },
                {
                    id: 2,
                    image: 'https://i.postimg.cc/FHNpL0kG/Screenshot-20211214-062856-1.jpg',
                    Person: 'Zimasile Wiseman Ngcukana',
                    words: 'Tyvon is not one who gives up, also a focused person and works towards bettering himself. He is extremely creative and can implement hes creativeness in his work.',
                },
                {
                    id: 3,
                    image: 'https://i.postimg.cc/BQgDRktc/DSC-3622.jpg',
                    Person: 'Lazola',
                    words:'Tyvon is a very talented young man. He is always willing to help hes peers with their work. He has a passion for web-designing and has a very creative eye.',
                },
                {
                    id: 4,
                    image: 'https://i.postimg.cc/DZTwvfMW/candice-2022.jpg',
                    Person: 'Candice Amon',
                    words: 'Tyvon is a very creative individual. He always puts in great effort to spice things up. He has a very colorful vibe and his character lights up the environment he finds himself in which reflects in the work he does.',
                },
                {
                    id: 5,
                    image: 'https://i.postimg.cc/br2HXZxW/joel.jpg',
                    Person: 'Joel Mukanya',
                    words: 'Tyvon is a very creative and well-behaved student. He does enjoy working with his classmates and works well on his project. He has gained knowledge of web development, including Bootstrap 5, and I am very delighted with the effort he puts into his work. I recommend him as a developer.',
                }
            ]
        }
    },
}
</script>
<style>

    
</style>