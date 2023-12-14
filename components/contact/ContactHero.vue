<template>
    <div class="bg-secondary flex justify-center items-center lg:px-[80px] px-[16px] ">
    <div class=" pb-[40px] md:pb-[80px] pt-[160px] w-[1280px]     ">
        <div class="w-full ">
                <div class="flex flex-col justify-center items-center gap-[40px]">
                    <div class="gap-[4px]">
                        <h3 class="text-[18px] font-[400] leading-[28px] text-white text-center">Contact us</h3>
                        <h1 class="text-white  font-[600] text-[28px] lg:text-[40px] text-center leading-[44px] lg:leading-[56px]">We're here for you</h1>
                        <p class="text-white text-[16px] font-[400] text-center leading-[28px]">Our friendly team are always ready to help you.</p>
                    </div>
                    <div class="hidden custom_bg w-full   h-[480px] rounded-[24px] md:flex justify-center items-center ">
                        <div class="lg:w-[848px] grid grid-cols-3  gap-[24px]">
                            <div class="px-[24px] h-[280px] lg:w-[280px] rounded-[8px] py-[16px] bg-white flex flex-col   gap-[10px]">
                                <div class="bg-primary w-fit text-white py-3 px-4 rounded-xl">
                                    <span><i class="pi pi-comment"></i></span>
                                </div>
                                <div class="">
                                    <h3 class="text-[16px] leading-[32px] font-[600] text-darkGreen">Email</h3>

                                    <p class="leading-[30px] text-[14px] text-darkGreen">Send Us a Private Message</p>
                                    <span class="underline text-[400] leading-[30px]  ">  <a href = "mailto:hello@upaenergy.org">hello@upaenergy.org</a></span>
                                </div>
                             
                            </div>
                            <div class="px-[24px] h-[280px] lg:w-[280px] rounded-[8px] py-[16px] bg-white flex flex-col gap-[10px]">
                                <div class="bg-primary w-fit text-white py-3 px-4 rounded-xl">
                                    <span><i class="pi pi-phone"></i></span>
                                </div>
                                <div>
                                    <h3 class="text-[16px] leading-[32px] font-[600] text-darkGreen">Telephone</h3>


                                    <p class="leading-[30px] text-[14px] text-darkGreen">Schedule a Call With Us</p>
                                    <p class="underline text-[400] leading-[30px]"><a href="tel:+23480033471271">+234 803 347 1271</a></p>
                                    <p class="underline text-[400] leading-[30px]"><a href="tel:+23480033471271">+234 09-2904317</a></p> 

                                </div>
                              
                            </div>
                            <div class="px-[24px] h-[280px] lg:w-[280px] rounded-[8px] py-[16px] bg-white flex flex-col gap-[10px]">
                                <div class="bg-primary w-fit text-white py-3 px-4 rounded-xl"> 
                                    <span><i class="pi pi-map-marker"></i></span>
                                </div>
                                <div>
                                    <h3 class="text-[16px] leading-[32px] font-[600] text-darkGreen">Address</h3>

                                    <p class="leading-[30px] text-[14px] text-darkGreen">Send Us a Private Message</p>
                                    <p class="underline text-[400] leading-[30px]">Plot 21 A.E.Ekukinam Street,Wing B 3rd floor,Deo-Gratias Plaza,Utako, FCT-Abuja.</p>

                                </div>
                              
                            </div>
                        </div>
                    </div>
                    <div class="w-full grid grid-cols-1 md:hidden gap-[40px] ">
                            <div class="px-[24px] h-[280px]  rounded-[8px] py-[16px] bg-white flex flex-col gap-[40px]">
                                <div>
                               
                                </div>
                                <div>
                                    <h3 class="text-[16px] leading-[32px] font-[600] text-darkGreen">Email</h3>
                                    <p class="leading-[30px] text-[14px] text-darkGreen">Send us a private message</p>

                                    <p class="underline text-[400] leading-[30px] text-primary"> <a href = "mailto:hello@upaenergy.org">hello@upaenergy.org</a></p>

                                </div>
                             
                            </div>
                            <div class="px-[24px] h-[280px]  rounded-[8px] py-[16px] bg-white flex flex-col gap-[40px]">
                                <div>
                                    
                                </div>
                                <div>
                                    <h3 class="text-[16px] leading-[32px] font-[600] text-darkGreen">Telephone</h3>


                                    <p class="leading-[30px] text-[14px] text-darkGreen">Schedule a Call With Us</p>
                                    <p class="underline text-[400] leading-[30px]"><a href="tel:+23480033471271">+234 803 347 1271</a></p>
                                    <p class="underline text-[400] leading-[30px]"><a href="tel:+23480033471271">+234 09-2904317</a></p> 

                                </div>
                             
                            </div>
                            <div class="px-[24px] h-[280px]  rounded-[8px] py-[16px] bg-white flex flex-col gap-[40px]">
                                <div>
                             
                                </div>
                                <div>
                                    <h3 class="text-[16px] leading-[32px] font-[600] text-darkGreen">Address</h3>
                                    <p class="leading-[30px] text-[14px] text-darkGreen">Visit their office HQ</p>
                                    <Nuxt-link to="https://www.google.com/maps/search/Deo-Gratias+Plaza,+Wing+B,+3rd+floor+Plot+21A,+Ekukinam+Street+Opp,+Utako+Market,+Abuja./@9.0670457,7.4424159,17z/data=!3m1!4b1?entry=ttu"  
                                    class="underline text-[400] leading-[30px] text-primary cursor-pointer">
                                        Plot 21 A.E.Ekukinam Street,Wing B 3rd floor,Deo-Gratias Plaza,Utako, FCT-Abuja..
                                    </Nuxt-link>
                                </div>
                              
                            </div>
                    </div>
                </div>
                

          
        </div>
        </div>
    </div>
</template>
<style scoped>
    .custom_bg{
        background-image: linear-gradient(rgba(26,28,27,0.70),rgba(26,28,27,0.70)),url('/img/solarteam.jpg');
        background-position: center;
        background-size: cover;
    }
    @media(max-width:800px){
        .custom_bg{
            background: none;
        }
    }
 
</style>
