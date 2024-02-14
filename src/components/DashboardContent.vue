<template>
    <div class="p-6">
        <!-- Balance, Profits, and Losses Section -->
        <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-6">
            <!-- Balance Card -->
            <div class="p-4 bg-white rounded-lg shadow">
                <h2 class="text-lg font-semibold">Balance</h2>
                <p class="text-2xl">$5900.00</p>
            </div>
            <!-- Profits Card -->
            <div class="p-4 bg-white rounded-lg shadow">
                <h2 class="text-lg font-semibold">Profits</h2>
                <div class="flex items-center">
                    <p class="text-2xl">$950.00</p>
                    <p class="text-green-600 ml-2">(+56%)</p>
                </div>
            </div>
            <!-- Losses Card -->
            <div class="p-4 bg-white rounded-lg shadow">
                <h2 class="text-lg font-semibold">Losses</h2>
                <div class="flex items-center">
                    <p class="text-2xl">$450.00</p>
                    <p class="text-red-600 ml-2">(-56%)</p>
                </div>
            </div>
            <div class="p-4 bg-white rounded-lg shadow">
                <h2 class="text-lg font-semibold">currency</h2>
                <div class="flex items-center">
                    <p class="text-2xl">$450.00</p>
                    <p class="text-red-600 ml-2">(-56%)</p>
                </div>
            </div>
        </div>
        <!-- Team Members Section -->
        <CountriesStats />
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">

            <div class="mb-6">
                <div class="flex justify-between mb-4">
                    <h3 class="text-lg font-semibold">Team Members</h3>
                    <p class="text-sm font-semibold text-[#2464FC]">view all</p>
                </div>

                <div class="bg-[#FFFFFF] rounded-sm px-4 py-3 flex items-between w-full mb-4">

                    <img class="h-10 w-10 rounded-full" src="../assets/about.svg" alt="Team member photo">
                    <div class="ml-4">
                        <p class="text-md font-medium">Andrew Johnston</p>
                        <p class="text-sm text-gray-600">Manager</p>
                    </div>

                </div>

                <div class="bg-[#FFFFFF] rounded-sm px-4 py-3 flex items-between w-full mb-4">

                    <img class="h-10 w-10 rounded-full" src="../assets/about.svg" alt="Team member photo">
                    <div class="ml-4">
                        <p class="text-md font-medium">Andrew Johnston</p>
                        <p class="text-sm text-gray-600">Manager</p>
                    </div>

                </div>

                <div class="bg-[#FFFFFF] rounded-sm px-4 py-3 flex items-between w-full mb-4">

                    <img class="h-10 w-10 rounded-full" src="../assets/about.svg" alt="Team member photo">
                    <div class="ml-4">
                        <p class="text-md font-medium">Andrew Johnston</p>
                        <p class="text-sm text-gray-600">Manager</p>
                    </div>

                </div>

                <div class="bg-[#FFFFFF] rounded-sm px-4 py-3 flex items-between w-full mb-4">

                    <img class="h-10 w-10 rounded-full" src="../assets/about.svg" alt="Team member photo">
                    <div class="ml-4">
                        <p class="text-md font-medium">Andrew Johnston</p>
                        <p class="text-sm text-gray-600">Manager</p>
                    </div>

                </div>
            </div>
            <ComparisonChart />
        </div>

        <!-- Comparison Section -->
        <!-- ... You would implement the comparison chart or other components here ... -->

    </div>
</template>
  
<script>
import CountriesStats from './CountriesStats.vue';
import ComparisonChart from './ComparisonChart.vue';
export default {
    name: 'DashboardContent',
    components: { CountriesStats, ComparisonChart }
}
</script>
  
<style scoped>
/* Additional styles for DashboardContent */
</style>