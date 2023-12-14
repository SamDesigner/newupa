
<template>
    <div class="bg-grayBg ">
    <div >
    
       
            <div class="h-[100vh] ">
                <swiper
                    class="h-full"
                    :modules="modules"
                    :slides-per-view="1"
                    :loop="true"
                    :autoplay="{
                    delay: 4000,
                    disableOnInteraction: true,
                    }"
                    :pagination="{ clickable: true }"
                    @swiper="onSwiper"
                    @slideChange="onSlideChange"
                   
                >
                    <swiper-slide>
                       <div class="h-[100%] bg_2 px-[16px] md:px-[40px] lg:px-[80px]">
                            <div class="h-full w-full flex justify-center items-center md:justify-start">

                                <CarouselText />

                            </div>
                       </div>
                    </swiper-slide>
                    <swiper-slide>
                       <div class="h-[100%] bg_3 px-[16px] md:px-[40px] lg:px-[80px]">
                        <div class="h-full w-full flex justify-center items-center md:justify-start">

                            <CarouselText />
                            

                            </div>
                       </div>
                    </swiper-slide>
                    <swiper-slide>
                       <div class="h-[100%] bg_1 px-[16px] md:px-[40px] lg:px-[80px]">
                        <div class="h-full w-full flex justify-center items-center md:justify-start">
                            <CarouselText />
                        </div>
                       </div>
                    </swiper-slide>
                   
                 
                
                

                   


            </swiper>        
                
            </div>
        </div>
       
    </div>
</template>
<style scoped>
    .carousel_img{
        object-fit:cover ;
    }
 
    
    .bg_1{
        background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.8)) ,url('/img/bulb_bg.jpg');
        background-position:top;
        background-size:cover
    }   
    .bg_2{
        background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.8)) , url('/img/newtwo.jpg');
        background-position:center;
        background-size:cover
    }   
    .bg_3{
        background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.8)) , url('/img/newthree.jpg');
        background-position:center;
        background-size:cover
    }   
</style>
<script>
   import { Navigation, Pagination, Scrollbar, A11y, Autoplay } from 'swiper/modules';

    // Import Swiper Vue.js components
    import { Swiper, SwiperSlide } from 'swiper/vue';

    // Import Swiper styles
    import 'swiper/css';
    import 'swiper/css/navigation';
    import 'swiper/css/pagination';
    import 'swiper/css/scrollbar';

    // Import Swiper styles
    export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        const onSwiper = (swiper) => {
        console.log(swiper);
        };
        const onSlideChange = () => {

        };
        return {
        onSwiper,
        onSlideChange,
        modules: [Navigation, Pagination, Scrollbar, A11y , Autoplay ,],
        };
    },
    };
</script>
