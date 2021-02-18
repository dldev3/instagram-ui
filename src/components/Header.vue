<template>
    <div class="flex justify-between p-3 shadow-md">
        <div>
            <p><span class="material-icons header-font-size-cam">camera_alt</span></p>
        </div>

        <div>
             <img class="w-18 h-12 ml-8" src="../assets/images/Instagram_logo.svg" alt="">
        </div>
        
        <div class="flex ">
            <img class="h-12 mr-3" src="../assets/images/igtv.svg" alt="">
            <p>
            <span 
            class="material-icons transform -rotate-45 header-font-size-send">
            send
            </span></p>
        </div>

    </div>
</template>
<script>
export default {
    name: "Header"
}
</script>


