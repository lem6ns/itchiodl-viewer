<div class="shadow-lg channel-bar">
    <ChannelTitle title={"lemons"}/>
    <div class="channel-container">
        <Category category={"game"} channels={["epic-game-1", "epic-game-2"]}/>
        <!-- category values: game, assets, game_mod, physical_game, soundtrack, tool, comic, book, other -->
    </div>
</div>

<script>
    import Category from "./Category.svelte";
    import ChannelTitle from "./ChannelTitle.svelte";
</script>