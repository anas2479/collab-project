<div class="">
    {#each work as piece}
        <div class="rounded-2xl min-h-[200px] flex justify-center ">
            
            <img src={piece} alt="" class=" mx-auto">

            
        </div>
    {/each}
</div>

<script>
    export let work = [];
</script>