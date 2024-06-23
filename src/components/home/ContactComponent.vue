<script setup>

</script>

<template>
    <main class="contact my-30 p-5">
        <h2 class="text-slate-900 p-4 font-bold text-center text-4xl mb-5">MY CONTACT</h2>
        <div class="contact-us text-slate-100 flex justify-around w-10/12 mx-auto bg-slate-900/50 rounded-lg p-5">
                
            <div class="get-in-touch w-5/12 pt-5">
                <h3 class="font-bold text-3xl font-mono">Get-in-Touch</h3>
                <div class="contact-info py-3 my-5">
                    <p class="py-2">Address: <br> <span><address class="p-0 m-0">Ikot Obio Nkan Road, Obot Idim, Ibesikpo Asutan Akwa Ibom State, Nigeria</address></span></p>
                    <p class="py-2 my-2"><span>Email: </span><br>goodlucketim94@gmail.com</p>
                    <p class="py-2 my-2"><span>Phone: </span><br>+234-9066600060</p>
                </div>
                <div class="socials py flex gap-5">
                    <p>Facebook</p>
                    <p>X</p>
                    <p>Whatsapp</p>
                    <p>Instagram</p>
                    <p>LinkedIn</p>
                    <p>TikTok</p>
                </div>
            </div>
            <div class="send-message w-5/12 pt-5">
                <h3 class="font-bold text-3xl font-mono">Send a Message</h3>
                <hr class="w-2/6">
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