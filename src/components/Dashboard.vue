<template>
  <div class="flex h-screen bg-gray-200">
    <!-- Sidebar Component -->
    <Sidebar />

    <!-- Main Content Area Component -->
    <div class="flex-1 flex flex-col overflow-hidden">
      <header class="flex justify-between items-center p-6 bg-white border-b border-gray-200">
        <!-- Header Content -->
        <h1 class="text-4xl font-bold text-gray-800">Dashboard</h1>
        <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
          Add Unit
        </button>
      </header>

      <main class="flex-1 overflow-x-hidden overflow-y-auto bg-gray-200">
        <DashboardContent />
      </main>
    </div>
  </div>
</template>

<script>
import Sidebar from './Sidebar.vue'
import DashboardContent from './DashboardContent.vue'

export default {
  name: 'Dashboard',
  components: {
    Sidebar,
    DashboardContent
  }
}
</script>

<style>
/* Global styles can be placed here */
</style>