<template>
    <div style="backgroundImage:url('./src/assets/contact.svg')" class=" font-Poppins ">
        <div class="w-full h-[130vh] flex align-middle justify-between items-start p-10">
            <div class="mt-[120px]">
                <img src="../assets/contact2.svg" class=" scale-90" alt="">
            </div>
    
            <div class="w-[700px] h-[690px] px-20 py-10 bg-white shadow-2xl">
                <h1 class="text-center text-3xl font-bold mb-5">Send Us Message</h1>
                <form class='flex flex-col'>
                    <input class='border-b-2 border-black my-3 p-2' type="email" name="email" placeholder='Your Email*' />
                    <input class='border-b-2 border-black my-3 p-2' type="text" name="name" placeholder='Your Name*' />
                    <input class='border-b-2 border-black my-3 p-2' type="number" name="Number" placeholder='Phone Number*' />
                    <input class='border-b-2 border-black my-3 p-2' type="text" name="subject" placeholder='Subject' />
                    <textarea class='border-b-2 border-black my-3 p-2' rows="4" type="text" name="message" placeholder='Your Message' />
                    <div class="flex items-center gap-4 w-96">
                        <input class='border-b-2 w-10 h-10 border-black my-4 p-2' type="checkbox">
                        <p class="text-sm">By sending this message, you confirm that you have read and agreed to our privacy-policy.</p>
                    </div>
                    <button className='bg-[#0E77FF] text-white px-6 py-4 rounded-[28px] mt-4 w-44 text-center' >Get Started >></button>
                </form>
            </div>
        </div>

        <div class="flex justify-around text-white">        
            <div class="w-[459px]">Lorem Finaldream rure dolor in reprehenderit in voluptate velit esse cillum dolore e uis nostrud exercitation isi ut aliquip ex ea commodo consequat.

                <div class="flex mt-3 gap-2">
                    <img src="../assets/twitter.svg" alt="">
                    <img src="../assets/twitter.svg" alt="">
                    <img src="../assets/instagram.svg" class="border-2 border-white rounded-[100%] px-2" alt="">
                </div>

            </div>

            <div class="-pt-8">
                <h1 class="font-bold border-b-4 mb-5 pb-3 border-[#21B3FF]">Our Servies</h1>
                <ul class="text-sm">
                    <li>Web Development</li>
                    <li class="pt-2">Mobile Development</li> 
                    <li class="pt-2">Cloud Technologies</li> 
                    <li class="pt-2">UI/UX Designs</li> 
                </ul>
            </div>

            <div class="-pt-12">
                <h1 class="font-bold mb-5 pb-3 border-b-4 border-[#21B3FF]">Our Links</h1>
                <ul class="text-sm">
                    <li>Terms & Conditions</li>
                    <li class="pt-2">Privacy Policy</li> 
                    <li class="pt-2">Imprint</li> 
                    <li class="pt-2">Legal</li> 
                </ul>
            </div>
            
            <div class="w-56 -pt-11">
                <h1 class="font-bold border-b-4 border-[#21B3FF] mb-5 pb-3">Contact Us</h1>
                <ul class="text-sm">
                    <li class="flex gap-3"> <img src="../assets/location.svg" alt=""> Al. Dummyodl 124/23 floor 123 Banswara Street, 02-577 India.</li>
                    <li class="py-2 flex gap-3"> <img src="../assets/call.svg" alt=""> 00 1800 245 453</li> 
                    <li class="flex gap-3"><img src="../assets/msg.svg" alt=""> hello@inkyy.com</li> 
                </ul>
            </div>

        </div>
    </div>

</template>

<script setup>

</script>
