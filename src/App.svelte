<NavBar />
<ChannelBar />
<TopBar />

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

        .channel-bar {
            @apply w-80 h-auto m-0 ml-16 bg-gray-200 dark:bg-gray-800
            overflow-hidden;
        }

        .channel-container {
            @apply flex flex-col items-center justify-start 
            p-1 m-0;
        }
        
        .channel-title {
            @apply flex items-center justify-center 
            h-16 
            m-0 p-0;
        }

        .channel-title-text {
            @apply text-lg tracking-wider font-bold 
            text-gray-600 dark:text-gray-400 
            mr-auto ml-4 my-auto align-middle;
        }

    }
</style>

<script>
    import NavBar from "./components/NavBar/NavBar.svelte";
    import ChannelBar from "./components/Channel/ChannelBar.svelte";
    import TopBar from "./components/TopBar.svelte";
    import View from "./components/View.svelte";
    import Popup from "./components/Popup.svelte";
</script>