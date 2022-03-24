<script>
    import NavBarIcon from "./NavBarIcon.svelte";
    import Divider from "./Divider.svelte";
</script>

<div
    class="fixed top-0 left-0 flex flex-col w-16 h-screen m-0 text-white shadow bg-primary"
>
    <NavBarIcon
        icon={`<svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" viewBox="0 0 20 20" fill="currentColor">
            <path d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z" />
        </svg>`} tooltip={"Home"} />
    <Divider />
    <NavBarIcon icon={`<img src="https://cdn.discordapp.com/avatars/407348579376693260/a071efa4ff242d554fd7848bf377e5b4.png?size=1024" alt="Creator"></img>`}/>
</div>
