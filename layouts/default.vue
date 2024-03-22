<template>
    <div class="container mx-auto max-w-4xl selection:bg-green-700 selection:text-zinc-50">
        <AppHeader />
        <main class="my-10">
            <slot />
        </main>
    </div>
</template>
  
<script setup>
// Link to Google Fonts
// useHead({
//     link: [
//         {
//             rel: 'preconnect',
//             href: 'https://fonts.googleapis.com'
//         },
//         {
//             rel: 'stylesheet',
//             href: 'https://fonts.googleapis.com/css2?family=Inter&display=swap',
//             crossorigin: ''
//         }
//     ]
// })
</script>
<style>
/* Set the font family for the entire site */
body {
    font-family: 'Inter' sans-serif;
}

/* Set the background color for the entire site */
body {
    @apply dark:bg-zinc-900 bg-zinc-50 dark:text-zinc-50 text-zinc-900
}
</style>