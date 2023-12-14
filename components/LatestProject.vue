<template>
    <div class="bg-grayBg py-[80px] px-[16px] flex flex-col gap-[60px]">
            <div class="max-w-[1440px] mx-auto space-y-4 md:space-y-0 grid grid-cols-1 md:grid-cols-2 items-center">
                <div 
                data-aos="fade-right"
                data-aos-easing="linear"
                data-aos-duration="1500"
                class="flex flex-col gap-[12px]">
                    <h3 class="text-primary">Innovation, Quality and Continous Improvement</h3>
                    <h1 class=" text-[28px] lg:text-[45px] font-[600px]">Latest Project, Solutions And Energy Supplies</h1>
                </div>
                <div 
                data-aos="fade-left"
                data-aos-easing="linear"
                data-aos-duration="1500"
                class="flex flex-col gap-[16px]">
                    <p class="text-gray-700 text-[16px] md:text-[18px] leading-[28px] ">Our sales offices and warehouses include PV industry experience enables us to provide in-depth material sourcing and supply chain expertise for every production & installation process.</p>
                    <button class="bg-primary text-white w-fit py-[20px] px-[25px]">Explore All Projects <span><i class="pi pi-arrow-right"></i></span></button>
                </div>
            </div>
            
            
                      
            <div class="max-w-[1440px] mx-auto grid md:grid-cols-2 lg:grid-cols-4 grid-cols-1 gap-[30px] mt-[20px]">
                <div class="">
                    <div class="h-[300px] w-full">
                        <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic1.jpg" />
                    </div>
                    <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                        <h3 class="text-black text-lg font-[400] text-primary">Solar Batteries</h3>
                        <div class="border w-[30px] border-b-darkYellow"></div>
                        <p class="text-[14px]">Our advanced solar batteries are designed to enhance the performance and extend the lifespan of your solar panels.</p>
                    </div>
                </div>
            
                <div class="">
                    <div class="h-[300px] w-full">
                        <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic2.jpg" />
                    </div>
                    <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                        <h3 class="text-black text-lg font-[400] text-primary">Inverters</h3>
                        <div class="border w-[30px] border-b-darkYellow"></div>
                        <p class="text-[14px]">Discover our durable inverter batteries, offering exceptional quality and reliability as the leading brand in Nigeria.</p>
                    </div>
                </div>
            
                <div class="">
                    <div class="h-[300px] w-full">
                        <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic3.jpg" />
                    </div>
                    <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                        <h3 class="text-black text-lg font-[400] text-primary">Installations</h3>
                        <div class="border w-[30px] border-b-darkYellow"></div>
                        <p class="text-[14px]">Get professional installations for your energy solutions, ensuring optimal performance for your systems.</p>
                    </div>
                </div>
            
                <div class="">
                    <div class="h-[300px] w-full">
                        <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic4.jpg" />
                    </div>
                    <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                        <h3 class="text-black text-lg font-[400] text-primary">Control Systems</h3>
                        <div class="border w-[30px] border-b-darkYellow"></div>
                        <p class="text-[14px]">Address basic gas concerns with our top-quality Control Systems, breaking scientific barriers for unparalleled performance.</p>
                    </div>
                </div>
            
                <div class="">
                    <div class="h-[300px] w-full">
                        <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic5.jpg" />
                    </div>
                    <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                        <h3 class="text-black text-lg font-[400] text-primary">Inverter Systems</h3>
                        <div class="border w-[30px] border-b-darkYellow"></div>
                        <p class="text-[14px]">Choose the best inverter batteries in Nigeria from UPA Energy for reliable power supply. Shop with us now and thank us later.</p>
                    </div>
                </div>
            
                <div class="">
                    <div class="h-[300px] w-full">
                        <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic3.jpg" />
                    </div>
                    <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                        <h3 class="text-black text-lg font-[400] text-primary">Maintenance</h3>
                        <div class="border w-[30px] border-b-darkYellow"></div>
                        <p class="text-[14px]">Engineered for longevity, UPA Energy's maintenance service ensures your solar infrastructure operates at peak performance. Our proactive approach, coupled with diagnostics, guarantees minimal downtime. Elevate your solar investment with UPA Energy Maintenance – where reliability meets innovation.</p>
                    </div>
                </div>
            </div>

        </div>
       
   
</template>

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
            console.log('slide change');
            };
            return {
            onSwiper,
            breakpoints: {
                
                320: {
                slidesPerView: 1,
                spaceBetween: 20
                },
                // when window width is >= 480px
                480: {
                slidesPerView: 2,
                spaceBetween: 30
                },
                // when window width is >= 640px
                640: {
                slidesPerView: 3,
                spaceBetween: 40
                }

            },
        onSlideChange,
        modules: [Navigation, Pagination, Scrollbar, A11y , Autoplay ,],
        };
    },
    };
</script>
<style scoped>
    .fit_img{
        object-fit:cover
    }
</style>
