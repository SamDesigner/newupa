<template>
    <div class="px-[16px] lg:px-[80px] py-[80px]" id="getstarted">
        <div class="max-w-[1440px] mx-auto flex flex-col gap-[40px]">
            <div 
            data-aos="fade-up"
            data-aos-easing="linear"
            data-aos-duration="1500"
            class="lg:w-[956px]">
                <h3 class="text-primary font-[400] leading-[28px] text-[18px]">Welcome</h3>
                <h1 class=" font-[600] text-[24px] md:text-[40px] ">We are commited to making a significant difference in Nigeria's energy landscape. We are proud to be a part of the solution that strengthens the nation.</h1>
            </div>
            
            <div 
            data-aos="fade-up"
            data-aos-offset="300"
            data-aos-duration="1500"
            class="h-[280px] md:h-[600px] w-full overflow-hidden rounded-3xl bg_custom">
                <img class="object_fit" src="/img/solarhandshake.jpg" />
            </div>

        </div>
    </div>
</template>

<style scoped>
    /* .bg_custom{
        background: url(' /img/solarhandshake.jpg ');
        background-position: center; 
        background-size: cover;
    } */
    .object_fit{
        object-fit: cover;
    }
</style>