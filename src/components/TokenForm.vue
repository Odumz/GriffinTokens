<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
</script>


<template>
    <div class="main flex justify-center">
        <form class="border rounded p-5 flex flex-col md:w-1/2 w-3/4">
            <div class="flex justify-between my-2">
                <label for="amount" class="font-bold">Stake Tokens</label>
                <p class="text-gray-500">Balance: 100</p>
            </div>
            <div class="input flex my-2">
                <input type="text" class="rounded-l border py-3 w-full">
                <span class="flex justify-center items-center border bg-gray-200 p-3 rounded-r text-gray-500">
                    <img src="../assets/dai.png" alt="mDai logo" class="w-1/3 mr-2">mDai
                </span>
            </div>
            <div class="flex flex-col">
                <button class="my-2 flex justify-center w-full text-lg py-2 rounded bg-blue-700 text-white">
                    STAKE
                </button>
                <button class="my-2 flex w-full py-2 justify-center rounded text-sm text-blue-700">
                    UN-STAKE...
                </button>
            </div>
        </form>
    </div>
</template>

