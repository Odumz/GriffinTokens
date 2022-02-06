<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
import TokenForm from './TokenForm.vue'
</script>


<template>
    <div class="md:mt-20 mt-10 px-lg-16 px-8 w-full flex justify-center text-gray-500">
        <table class="md:w-1/2 w-3/4">
            <thead>
                <tr class="flex justify-between items-center my-3 gap-2">
                    <th>Staking Balance</th>
                    <th>Reward Balance</th>
                </tr>
            </thead>
            <tbody>
                <tr class="flex justify-between items-center mt-3 mb-10">
                    <td>helo mDAI</td>
                    <td>helo GRFT</td>
                </tr>
            </tbody>
        </table>
    </div>
    <token-form />
</template>

