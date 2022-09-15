<template>
  <div :class="{'dark': darkMode}">
    <h1 class="text-red-500 dark:text-dim-100">salut</h1>
  </div>

  <div class="min-h-full">

    <div class="grid grid-cols-12 mx-auto sm:px-6 lg:px-8 lg:gap-5">

      <!-- sidebar gauche -->
      <div class="hidden bg-yellow-300 md:block xs-col-span-1 xl:col-span-2 ">
        <div class="sticky top-0">
          <SidebarLeft/>
        </div>
      </div>

      <!-- contenu principal -->

      <!-- sidebar droite -->

    </div>

  </div>


</template>

<script setup>
  
  const darkMode = ref(true)



</script>