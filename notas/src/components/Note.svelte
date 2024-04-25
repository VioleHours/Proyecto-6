<script>
    export let title;
    export let color;
    export let text;
</script>

<div class="Note">
    <div class="Note-container">
        <div class="header">
            <div class="options">
                <button>Color</button>
                <button>Delete</button>
            </div>
        </div>

        <div class="content">
            <div class="title">
                <input type="text" placeholder="No title..." bind:value={title}>
            </div>
            <div class="text">
                <textarea bind:value={text} name="" id="" cols="30" rows="10" placeholder="Write..."></textarea>
            </div>
        </div>
    </div>
</div>

<style>

</style>