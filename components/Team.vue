<template>
  <div class="max-w-[1440px] px-[16px] py-[40px] lg:px-[80px] mx-auto">
    <div class="flex flex-col gap-[50px]">
      <div class="flex flex-col items-center gap-[8px] justify-center">
        <h3 class="text-primary">Our Team</h3>
        <h1 class="text-[32px] font-bold">Meet Our Trusted Team</h1>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-[30px]">
        <div
          data-aos="fade-up"
          data-aos-offset="300"
          data-aos-duration="1500"
          class="shadow-md md:shadow-none"
        >
          <div class="h-[400px]">
            <img
              class="h-full img_fit w-full md:rounded-full"
              src="/img/ceo1.jpg"
              style="object-position: top center"
            />
          </div>
          <div class="py-[10px] flex justify-center flex-col items-center">
            <h1>Mr Uche Peters</h1>
            <h3 class="text-primary">CEO</h3>
          </div>
        </div>
        <div
          data-aos="fade-down"
          data-aos-offset="300"
          data-aos-duration="300"
          data-aos-easing="ease-in-sine"
          class="shadow-md md:shadow-none"
        >
          <div class="h-[400px]">
            <img
              class="h-full img_fit w-full md:rounded-full"
              src="/img/ceo2.jpg"
              style="object-position: top center"
            />
          </div>
          <div class="py-[10px] flex justify-center flex-col items-center">
            <h1>Mr Israel Adenuga</h1>
            <h3 class="text-primary">Director</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.img_fit {
  object-fit: cover;
}
</style>
