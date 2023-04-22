<template>
  <div class="container mx-auto">
    <div class="flex items-center justify-center h-screen">
      <div class="bg-[#4895ef] flex flex-col py-5 rounded-lg">
        <div class="flex flex-row justify-end">
          <svg class="w-5 h-5 fill-white hover:fill-gray-200 hover:cursor-pointer" viewBox="0 0 24 24"><path d="m19.6 21l-6.3-6.3q-.75.6-1.725.95T9.5 16q-2.725 0-4.612-1.888T3 9.5q0-2.725 1.888-4.612T9.5 3q2.725 0 4.612 1.888T16 9.5q0 1.1-.35 2.075T14.7 13.3l6.3 6.3l-1.4 1.4ZM9.5 14q1.875 0 3.188-1.313T14 9.5q0-1.875-1.313-3.188T9.5 5Q7.625 5 6.312 6.313T5 9.5q0 1.875 1.313 3.188T9.5 14Z"/></svg>
          <svg class="w-5 h-5 fill-white hover:fill-gray-200 hover:cursor-pointer" viewBox="0 0 24 24"><path fill-rule="evenodd" d="M9.024 2.783A1 1 0 0 1 10 2h4a1 1 0 0 1 .976.783l.44 1.981c.4.19.781.41 1.14.66l1.938-.61a1 1 0 0 1 1.166.454l2 3.464a1 1 0 0 1-.19 1.237l-1.497 1.373a8.1 8.1 0 0 1 0 1.316l1.497 1.373a1 1 0 0 1 .19 1.237l-2 3.464a1 1 0 0 1-1.166.454l-1.937-.61c-.36.25-.741.47-1.14.66l-.44 1.98A1 1 0 0 1 14 22h-4a1 1 0 0 1-.976-.783l-.44-1.981c-.4-.19-.781-.41-1.14-.66l-1.938.61a1 1 0 0 1-1.166-.454l-2-3.464a1 1 0 0 1 .19-1.237l1.497-1.373a8.097 8.097 0 0 1 0-1.316L2.53 9.97a1 1 0 0 1-.19-1.237l2-3.464a1 1 0 0 1 1.166-.454l1.937.61c.36-.25.741-.47 1.14-.66l.44-1.98zM12 15a3 3 0 1 0 0-6a3 3 0 0 0 0 6z" clip-rule="evenodd"/></svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
// APIs im going to use for the app
// https://geocoding-api.open-meteo.com/v1/search?name=Berlin&count=10&language=en&format=json - Fetch the user queried location
// https://api.open-meteo.com/v1/forecast? - Fetch weather data for that location
</script>

<style scoped></style>
