<template>
  <div :class="{'dark': darkMode}">
    
    <div class="bg-white dark:bg-dim-900">

      
      <div class="min-h-full">

        <div class="grid grid-cols-12 mx-auto sm:px-6 lg:px-8 lg:gap-5">

          <!-- sidebar gauche -->
          <div class=" md:block xs-col-span-1 xl:col-span-2 ">
            <div class="sticky top-0">
              <SidebarLeft/>
            </div>
          </div>

          <!-- contenu principal -->

          <!-- sidebar droite -->

        </div>

      </div>



    </div>


  </div>


</template>

<script setup>
  
  const darkMode = ref(false)



</script>