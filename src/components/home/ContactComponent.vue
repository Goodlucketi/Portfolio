<script setup>
    import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
    import { faFacebook } from '@fortawesome/free-brands-svg-icons'
    import { faTwitter } from '@fortawesome/free-brands-svg-icons'
    import { faLinkedin } from '@fortawesome/free-brands-svg-icons'
    import { faWhatsapp } from '@fortawesome/free-brands-svg-icons'
    import { faInstagram } from '@fortawesome/free-brands-svg-icons'
    import { faEnvelope } from '@fortawesome/free-solid-svg-icons'
    import { faLocationDot } from '@fortawesome/free-solid-svg-icons'
    import { faPhone } from '@fortawesome/free-solid-svg-icons'
</script>

<template>
    <main class="contact my-30 p-5">
        <h2 class="text-slate-900 p-4 font-bold text-center text-4xl mb-5">MY CONTACT</h2>
        <div class="contact-us text-slate-100 md:flex md:justify-around md:w-10/12 mx-auto bg-slate-900/50 rounded-lg p-5">
                
            <div class="get-in-touch md:w-5/12 pt-5" data-aos="flip-right" data-aos-duration="2000">
                <h3 class="font-bold text-3xl font-mono">Get-in-Touch</h3>
                <div class="contact-info py-3 my-5">
                    <p class="py-2 italic text-sm md:text-lg"><FontAwesomeIcon :icon="faLocationDot" size="lg"/> <span>Ikot Obio Nkan Road, Obot Idim, Ibesikpo Asutan Akwa Ibom State, Nigeria</span></p>
                    <p class="py-2 my-2 text-sm md:text-lg"><span><FontAwesomeIcon :icon="faEnvelope" size="lg"/> </span> goodlucketim94@gmail.com</p>
                    <p class="py-2 my-2 text-sm md:text-lg"><span><FontAwesomeIcon :icon="faPhone" size="lg"/> </span> +234-9066600060</p>
                </div>
                <div class="socials flex gap-2">
                    <p><a href="https://www.facebook.com/goodlucketi"><FontAwesomeIcon :icon="faFacebook" size="lg"/></a></p>
                    <p><a href="https://www.twitter.com/goodlucketi"><FontAwesomeIcon :icon="faTwitter" size="lg"/></a></p>
                    <p><a href="https://www.linkedin.com/goodlucketi"><FontAwesomeIcon :icon="faLinkedin" size="lg"/></a></p>
                    <p><a href="https://www.whatsapp.com/goodlucketi"><FontAwesomeIcon :icon="faWhatsapp" size="lg"/></a></p>
                    <p><a href="https://www.instagram.com/goodlucketi"><FontAwesomeIcon :icon="faInstagram" size="lg"/></a></p>
                </div>
            </div>
            <div class="send-message my-5 md:w-5/12 pt-5" data-aos="flip-left" data-aos-duration="2000">
                <h3 class="font-bold text-3xl font-mono">Send a Message</h3>
                <hr class="w-2/6 h-1 bg-white">
                <form class="message my-3 py-3 ">
                    <input type="text" name="sender-name" id="sender-name" placeholder="Your Name" class="block p-3 rounded-md mb-5 w-full bg-transparent border">
                    <input type="email" name="sender-email" id="sender-email" placeholder="Your Email" class="block p-3 rounded-md mb-5 w-full bg-transparent border">
                    <input type="text" name="sender-phone" id="sender-phone" placeholder="Your Phone" class="block p-3 rounded-md mb-5 w-full bg-transparent border">
                    <input type="text" name="subject" id="subject" placeholder="Message Subject" class="block p-3 rounded-md mb-5 w-full bg-transparent border">
                    <textarea name="message" id="message" placeholder="Your message" class="block p-3 rounded-md my-5 w-full bg-transparent border"></textarea>

                    <input type="submit" value="Send Message" class="p-3 bg-slate-400 text-white block rounded-md w-full">
                </form>
            </div>
            
        </div>
    </main>
</template>

<style scoped>
   .contact{
    background: linear-gradient(90deg, rgba(215, 227, 243, 0.452), rgba(151, 168, 175, 0.644), rgba(191, 230, 191, 0.603)), url('../../assets/images/work-3.jpg') no-repeat;
        background-size: cover;
        background-attachment: fixed;
   }
   /* input::placeholder, textarea::placeholder{
    color: rgb(0, 0, 0);
   } */
</style>