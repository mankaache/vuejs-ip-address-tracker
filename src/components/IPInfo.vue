<template>
    <div class="absolute -bottom-64 lg:-bottom-20 
    flex flex-col lg:flex-row bg-white gap-y-4 
    gap-x-12 px-8 pt-8 pb-12 rounded-md">
        <!-- flex item #1 -->
        <div class="flex flex-col">
            <h3 class="text-xs mb-2 uppercase">IP Address</h3>
            <span class="text-xl font-bold" > 8.8.8.8</span>
        </div>
        <!-- flex item #2 -->
        <div class="flex flex-col">
            <h3 class="text-xs mb-2 uppercase">Location</h3>
            <span class="text-xl font-bold" > Cameroon</span>
        </div>
         <!-- flex item #3  -->
        <div class="flex flex-col">
            <h3 class="text-xs mb-2 uppercase">TimeZone</h3>
            <span class="text-xl font-bold" > Gmt +1</span>
        </div>
         <!-- flex item #4  -->
        <div class="flex flex-col">
            <h3 class="text-xs mb-2 uppercase">ISP</h3>
            <span class="text-xl font-bold" >Google</span>
        </div>
    </div>
       
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>