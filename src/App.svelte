<NavBar />

<main class="flex justify-center">
    <h1>ben</h1>
</main>

<style global lang="postcss">
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

    @layer components {
        
        .nav-icon {
            @apply relative flex items-center justify-center
            h-12 w-12 mt-2 mb-2 mx-auto shadow-lg
            bg-gray-800 text-white hover:bg-secondary
            rounded-3xl hover:rounded-xl cursor-pointer
            transition-all duration-150 ease-linear;
        }

        .nav-icon img {
            @apply rounded-3xl hover:rounded-xl
            transition-all duration-150 ease-linear;
        }

        .nav-tooltip {
            @apply absolute w-auto p-2 m-2 min-w-max left-14
            rounded-md shadow-md
            text-white bg-gray-900
            text-sm font-bold
            transition-all duration-100 scale-0 origin-left;
        }

        .nav-hr {
            @apply bg-gray-200 dark:bg-gray-800 
            border border-gray-200 dark:border-gray-800
            rounded-full mx-2;
        }
    }
</style>

<script>
    import NavBar from "./components/NavBar/NavBar.svelte";
    import View from "./components/View.svelte";
    import Popup from "./components/Popup.svelte";
</script>