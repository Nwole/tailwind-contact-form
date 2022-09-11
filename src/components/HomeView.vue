<template>
  <div class="antialiasee bg-gray-100">
    <div class="flex w-full min-h-screen justify-center items-center">
        <div class=" flex flex-col md:flex-row md:space-x-6 md:space-y-0  space-y-6 bg-cyan-700 w-full max-w-4xl p-8 rounded-xl shadow-lg text-white overflow-hidden">
            <div  class="flex flex-col space-y-8 justify-between">
                <div>
                     <h1 class="font-bold text-4xl tracking-wide">Contact Us</h1>
                     <p class="pt-2 text-cyan-100 text-sm">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut magnam nobis iste totam, suscipit rerum eius consectetur!</p>
                </div>
                <div class="flex flex-col space-y-6">
                    <div class="inline-flex items-center space-x-2">
                        <v-icon style="color:aquamarine">mdi-phone</v-icon>
                        <span>(+123) 3547589664</span>
                    </div>
                     <div class="inline-flex items-center space-x-2">
                        <v-icon style="color:aquamarine">mdi-email-outline</v-icon>
                        <span>contact@xyzwebsite.com</span>
                    </div>
                     <div class="inline-flex items-center space-x-2">
                        <v-icon style="color:aquamarine">mdi-map-marker</v-icon>
                        <span>11, Street 343, Abcd Fgh </span>
                    </div>
                </div>
                <div  class="flex  space-x-4 text-xl">
                    <a href="#"><v-icon style="color: white; ">mdi-facebook</v-icon></a>
                     <a href="#"><v-icon style="color:white">mdi-twitter</v-icon></a>
                    <a href="#"><v-icon style="color:white">mdi-instagram</v-icon></a>
                    <a href="#"><v-icon style="color:white">mdi-linkedin</v-icon></a>
                </div>
            </div>
            <div class="relative"> 
                <div class="absolute z-0 w-40 h-40 bg-teal-400 rounded-full -right-28 -top-28">

                </div>
                 <div class="absolute z-0 w-40 h-40 bg-teal-400 rounded-full -left-28 -bottom-16">
                    
                </div>
            <div class="relative z-10 bg-white md:w-80 text-gray-600 rounded-lg shadow-lg mt-8 p-8">
                <form action="" class="flex flex-col space-y-4">
                    <div>
                         <labe for="" class="text-sm">Your name</labe>
                        <input type="text" placeholder="Your name" class="ring-1 ring-gray-300 shadow-sm w-full rounded-md px-4 py-2 outline-none mt-2 focus:ring-2 focus:ring-teal-600 placeholder-orange-500 focus:placeholder-blue-500 "/>
                    </div>
                    <div>
                        <labe for="" class="text-sm">Email Address</labe>
                        <input type="text" placeholder="Your name" class="ring-1 ring-gray-300 shadow-sm w-full rounded-md px-4 py-2 outline-none mt-2 focus:ring-2 focus:ring-teal-600 placeholder-orange-500 focus:placeholder-blue-500 "/>
                    </div>
                    <div>
                        <labe for="" class="text-sm">Message</labe>
                        <textarea type="text" rows="4" placeholder="Message" class="ring-1 ring-gray-300 shadow-sm w-full rounded-md px-4 py-2 outline-none mt-2 focus:ring-2 focus:ring-teal-600 placeholder-orange-500 focus:placeholder-blue-500"></textarea>
                    </div>
                    <button class="flex self-end rounded-lg text-white bg-cyan-700 font-bold px-6 py-2 uppercase text-sm">Send Message</button>
                </form>
            </div>
        </div>
        </div>    
    </div> 
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>