<template>
  <div class="relative">
    <div class="bg-white py-[80px] px-[16px] flex items-center justify-center">
      <div class="lg:max-w-[1440px] lg:px-[80px] flex flex-col gap-[40px] lg:flex-row justify-between">
        <div
          data-aos="fade-right"
          data-aos-offset="300"
          data-aos-easing="ease-in-sine"
        >
          <div class="flex-1 lg:w-[576px] flex flex-col gap-[40px]">
            <div>
              <h1 class="text-darkGreen leading-[36px] md:leading-[48px] text-[20px] md:text-[32px] font-[600]">
                Let us give you a call
              </h1>
              <p class="text-[16px] leading-[28px] font-[400] text-darkGreen">
                Send us your details in the form below, and a member of our team
                will call you as soon as possible. If you’d like to speak to us
                straight away, call
                <span class="text-primary">+234 80033471271. 09-2904317</span>
                We’re available seven days a week.
              </p>
            </div>
            <div class="flex gap-[32px]">
              <!-- <img src="/svg/facebook.svg" />
                            <img src="/svg/linkedin.svg" />
                            <img src="/svg/twitter.svg" /> -->

                        </div>
                    
                    </div>
                    
                </div>
                <div
                data-aos="fade-left"
                data-aos-offset="300"
                data-aos-easing="ease-in-sine"
                >
                    <div class=" md:flex-1 lg:w-[576px] flex flex-col gap-[40px]">
                        <div class="flex flex-col gap-[12px]">
                            <h1 class="text-darkGreen font-[600] text-[20px] md:text-[32px] leading-[36px] md:leading-[48px]">Get In Touch</h1>
                            <p class="text-[16px] font-[400] leading-[24px] text-darkGreen">Our friendly team would love to hear from you</p>
                        </div>
                        <div 
                        
                        class="flex flex-col gap-[20px]">
                            <div class="flex flex-col md:flex-row gap-[20px]">
                                <div class="flex flex-col gap-[4px] w-full">
                                    <label class="text-[16px] font-[500] leading-[24px] text-darkGreen">Name</label>
                                    <input ref = "name" placeholder="John"  class="border border-inputGray text-[16px] font-[400] rounded-[8px] py-[16px] px-[24px]" />
                                </div>
                   
                            </div>

                            <div>
                                <div class="flex flex-col gap-[4px]">
                                    <label class="text-[16px] font-[500] leading-[24px] text-darkGreen">Phone number</label>
                                    <div class="border border-inputGray flex items-center gap-[4px] px-[24px] rounded-[8px]">
                             
                                        <input ref = "phoneNumber" placeholder="+1 (555) 000-000" class="outline-none text-[16px]   font-[400] w-full  py-[16px] " />
                                    </div>
                                    
                                </div>
                            </div>
                            <div>
                                <div class="flex flex-col gap-[4px]">
                                    <label class="text-[16px] font-[500] leading-[24px] text-darkGreen">Email Address</label>
                                    <input ref = "email" placeholder="you@company.com"  class="border border-inputGray text-[16px] font-[400] rounded-[8px] py-[16px] px-[24px]" />
                                </div>
                            </div>
                            <div>
                                <div class="flex flex-col gap-[4px]">
                                    <label class="text-[16px] font-[500] leading-[24px] text-darkGreen">Subject</label>
                                    <input ref = "subject" placeholder="Subject" class="border border-inputGray text-[16px] font-[400] rounded-[8px] py-[16px] px-[24px]" />
                                </div>
                            </div>
                            <div>
                                <div class="flex flex-col gap-[4px] ">
                                    <label class="text-[16px] font-[500] leading-[24px] text-darkGreen">Message</label>

                                    <textarea  ref = "message" id="w3review" name="w3review" rows="4"  placeholder="Leave us a message" class="h-[134px] text-black border border-inputGray text-[16px] rounded-[8px] py-[16px] px-[24px] ">
                                    
                                    </textarea>

                                </div>
                            </div>

                        
                            
                        </div>
                        <div class="flex justify-center">
                          <button
                            @click="sendEmail"
                            class="w-full md:w-[343px] bg-primary text-white rounded-[1000px] py-[14px] px-[32px]">
                            Send Message
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </template>
            
<script>
export default {
  methods: {
    sendEmail() {
      const subject = encodeURIComponent("Message from UPA Website");
      const body = encodeURIComponent(this.getMessageBody());
      const recipientEmail = "hellop@upaenergy"; // replace with your recipient's email address
      window.location.href = `mailto:${recipientEmail}?subject=${subject}&body=${body}`;
    },
    getMessageBody() {
      const name = this.$refs.name?.value || "";
      const phoneNumber = this.$refs.phoneNumber?.value || "";
      const subject = this.$refs.subject?.value || "";
      const message = this.$refs.message?.value || "";

      return `Name: ${name}\nPhone Number: ${phoneNumber}\nSubject: ${subject}\nMessage: ${message}`;
    },
  },
};
</script>

<style scoped>
.custom_index {
  z-index: 2000;
}
.custom_text {
  color: rgb(220, 8, 8) !important;
}
.custom_btn {
  background: rgb(220, 8, 8) !important;
}
.gradient_bg {
  background: rgba(0, 0, 0, 0.8);
}
.custom_greenText {
  color: rgb(10, 192, 125);
}
.customGreen {
  background: rgb(10, 192, 125);
}
</style>
