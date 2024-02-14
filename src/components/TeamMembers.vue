<template>
    <div class="bg-white p-4 rounded-lg shadow mb-6">
      <div class="flex justify-between">
        <h3 class="text-lg font-semibold">Team Membs</h3>
        <p class="text-lg font-semibold">view all</p>
      </div>
     
      <div class="space-y-4">
        <!-- Repeat this block for each team member -->
        <div class="flex items-center">
          <img class="h-10 w-10 rounded-full mr-4" src="/path-to-member-photo.jpg" alt="Member name" />
          <div>
            <p class="font-medium text-gray-800">Andr Johnston</p>
            <p class="text-sm text-gray-600">Manager</p>
          </div>
        </div>
        <!-- Additional team members... -->
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'TeamMembers'
    // You can include component data, computed properties, methods, etc. here.
  }
  </script>
  
  <style scoped>
  /* Additional styles for TeamMembers */
  </style>