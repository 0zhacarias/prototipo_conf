<script setup>
import PrimaryButton from "@/Components/PrimaryButton.vue";
</script>
<template>
    <!--
      This example requires updating your template:

      ```
      <html class="h-full">
      <body class="h-full">
      ```
    -->
    <main
        class="grid min-h-full place-items-center bg-white px-6 py-24 sm:py-32 lg:px-8"
    >
        <div class="text-center">
            <p class="text-base font-semibold text-indigo-600">404</p>
            <h1
                class="mt-4 text-3xl font-bold tracking-tight text-gray-900 sm:text-5xl"
            >
                Page not found
            </h1>
            <p class="mt-6 text-base leading-7 text-gray-600">
                Sorry, we couldn’t find the page you’re looking for.
            </p>
            <div class="mt-10 flex items-center justify-center gap-x-6">
                <a
                    href="#"
                    class="inline-flex items-center px-4 py-2 rounded-md bg-indigo-600 border border-transparent rounded-md font-semibold text-xs text-white uppercase tracking-widest hover:bg-gray-700 focus:bg-gray-700 active:bg-gray-900 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2 transition ease-in-out duration-150 focus-visible:outline-indigo-600"

                    >Go back home</a
                >
                <a href="#" class="text-sm font-semibold text-gray-900"
                    >Contact support <span aria-hidden="true">&rarr;</span></a
                >
            </div>
            <PrimaryButton class="ms-4"> Log in </PrimaryButton>
        </div>
    </main>
</template>
