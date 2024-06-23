<script setup>

</script>

<template>
    <main class="footer my-30 p-5">
        <div class="footer text-slate-100 flex gap-10 justify-center items-center w-10/12 mx-auto bg-slate-900/50 rounded-lg p-5">
            <div class="footer-info py-3 my-5 w-4/12">
                <p class="py-2">Address: <br> <span><address class="p-0 m-0">Ikot Obio Nkan Road, Obot Idim, Ibesikpo Asutan Akwa Ibom State, Nigeria</address></span></p>
                <p class="py-2 my-2"><span>Email: </span><br>goodlucketim94@gmail.com</p>
                <p class="py-2 my-2"><span>Phone: </span><br>+234-9066600060</p>
            </div>
            <div class="socials py w-4/12">
                <p>Facebook</p>
                <p>X</p>
                <p>Whatsapp</p>
                <p>Instagram</p>
                <p>LinkedIn</p>
                <p>TikTok</p>
            </div>
            <div class="send-message pt-5 w-4/12">
                <p class="text-xl font-mono">Subscribe to Newsletter</p>
                <label class="relative block">
                    <input type="email" name="newsletter-email" placeholder="Your Email" class="p-3 rounded-md mb-5 bg-transparent border w-full">
                    <input type="submit" value="Send Message" class="p-3 bg-slate-400 text-white rounded-md absolute top-0 right-0">
                </label>
            </div>
            
        </div>
    </main>
</template>

<style scoped>
   .footer{
    background: linear-gradient(90deg, rgba(11, 15, 20, 0.452), rgba(11, 18, 20, 0.644), rgba(4, 7, 4, 0.616)), url('../../assets/images/3203362.jpg') no-repeat;
        background-size: cover;
        background-attachment: fixed;
   }
  
</style>