<template>
    <footer class="px-2 pt-[80px] pb-[40px] md:px-6  mt-5 bg-secondary text-white space-y-6 text-xs" >
        <div class=" flex flex-col md:flex-row  justify-between">
            <div class="md:space-y-5">
                <h3 class=" md:text-[60px] font-bold">UPA</h3>
               
                
            </div>
    
           
          
            <div>
               
                <ul class="flex text-[18px] gap-[20px]">
                    <li>
                        <Nuxt-link to="/">Home</Nuxt-link>
                    </li>
                    <li>
                        <Nuxt-link to="/about">About Us</Nuxt-link>
                    </li>
                    <li>
                        <Nuxt-link to="/contact">Contact Us </Nuxt-link>
                    </li>
                    <li>
                        <Nuxt-link to="/services">Services</Nuxt-link>
                    </li>
                  
                   
                </ul>
               
            </div>
        </div>
        <div class="border border-white w-full ">

        </div>
        <div class="flex flex-col justify-center items-center  space-y-6 lg:space-y-0 ">
            <div class="flex flex-col  items-center gap-4 ">
                <ul class="flex items-center gap-4">
                    <li><i class="pi pi-twitter text-lg"></i></li>
                    <li><i class="pi pi-facebook text-lg"></i></li>
                    <li><i class="pi pi-linkedin text-lg"></i></li>
                    <li><i class="pi pi-instagram text-lg"></i></li>
                    <li><i class="pi pi-youtube text-lg"></i></li>
                    <li><i class="pi pi-globe text-lg"></i> EN</li>
                </ul>
                <div class="flex flex-col md:flex-row gap-4 items-center justify-center">
                
                    <p>&copy; Copyright 2023 UPA</p>
                    <ul class="flex items-center gap-3">
                        
                        <li><a href="#">Terms of service</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Manage Cookies</a></li>
                    </ul>
                </div>
            </div>
           
        </div>
    </footer>
</template>
<style scoped>
    @media(max-width:1200px){

    }
</style>
