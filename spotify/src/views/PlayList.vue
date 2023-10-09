<script setup>
//import { reactive } from 'vue';
import SideBar from '../components/SideBar.vue';

//const samuel_music = reactive({titulo: "samuel", album:"samuel", genero:"funk"})
</script>

<template>
<main class="flex flex-row">

    <SideBar></SideBar>

    <div class="max-w-sm w-full lg:max-w-full bg-fixed">
    <div style="background:linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(/samuel.jpg) no-repeat center;background-size:cover"
        class="py-52 px-1 md:px-8 text-center relative text-white font-bold text-2xl md:text-3xl overflow-auto">
        <h1 class="pb-4">Samuel<br>Playlist</h1>
    </div>
    <table class="w-full text-sm text-left text-gray-100 dark:text-gray-100">
        <thead class="text-xs text-black uppercase dark:text-gray-100">
            <tr>
                <th scope="col" class="px-6 py-3">
                    Titulo
                </th>
                <th scope="col" class="px-6 py-3">
                    Album
                </th>
                <th scope="col" class="px-6 py-3">
                    Adicionado em
                </th>
                <th scope="col" class="px-6 py-3">
                    Genero
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white dark:bg-black">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    Apple MacBook Pro 17"
                </th>
                <td class="px-6 py-4">
                    Silver
                </td>
                <td class="px-6 py-4">
                    Laptop
                </td>
                <td class="px-6 py-4">
                    $2999
                </td>
            </tr>
            <tr class="bg-white dark:bg-black">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    Microsoft Surface Pro
                </th>
                <td class="px-6 py-4">
                    White
                </td>
                <td class="px-6 py-4">
                    Laptop PC
                </td>
                <td class="px-6 py-4">
                    $1999
                </td>
            </tr>
            <tr class="bg-white dark:bg-black">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    Magic Mouse 2
                </th>
                <td class="px-6 py-4">
                    Black
                </td>
                <td class="px-6 py-4">
                    Accessories
                </td>
                <td class="px-6 py-4">
                    $99
                </td>
            </tr>
        </tbody>
    </table>
</div>
</main>
</template>