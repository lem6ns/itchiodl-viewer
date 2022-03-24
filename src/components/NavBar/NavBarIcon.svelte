<script>
    export let icon = "";
    export let tooltip = "cool tooltip";
</script>

<div class="nav-icon group">
    {@html icon}

    <span class="nav-tooltip group-hover:scale-100">
        {tooltip}
    </span>
</div>