<template>
    <div class="grid grid-cols-1 bg-white md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-4 mb-6">
      <!-- Italy -->
      <div class="bg-white p-4 rounded-lg shadow flex items-center justify-between">
        <div>
          <p class="text-md font-medium text-gray-700">Italy</p>
          <p class="text-lg font-semibold text-gray-900">475 <span class="text-green-500">↑</span></p>
        </div>
        <div class="text-green-500">
          <!-- Upward trend icon -->
        </div>
      </div>
  
      <!-- United States -->
      <div class="bg-white p-4 rounded-lg shadow flex items-center justify-between">
        <div>
          <p class="text-md font-medium text-gray-700">United States</p>
          <p class="text-lg font-semibold text-gray-900">431 <span class="text-green-500">↑</span></p>
        </div>
        <div class="text-green-500">
          <!-- Upward trend icon -->
        </div>
      </div>
  
      <!-- Canada -->
      <div class="bg-white p-4 rounded-lg shadow flex items-center justify-between">
        <div>
          <p class="text-md font-medium text-gray-700">Canada</p>
          <p class="text-lg font-semibold text-gray-900">174 <span class="text-red-500">↓</span></p>
        </div>
        <div class="text-red-500">
          <!-- Downward trend icon -->
        </div>
      </div>
  
      <!-- Spain -->
      <div class="bg-white p-4 rounded-lg shadow flex items-center justify-between">
        <div>
          <p class="text-md font-medium text-gray-700">Spain</p>
          <p class="text-lg font-semibold text-gray-900">475 <span class="text-green-500">↑</span></p>
        </div>
        <div class="text-green-500">
          <!-- Upward trend icon -->
        </div>
      </div>
  
      <!-- Add more countries as needed -->
    </div>
  </template>
  
  <script>
  export default {
    name: 'CountryStats'
    // You can include component data, computed properties, methods, etc. here.
  }
  </script>
  
  <style scoped>
  /* Additional styles for CountryStats */
  </style>