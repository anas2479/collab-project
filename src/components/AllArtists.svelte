<div class="flex flex-wrap gap-8">
    {#each data as artist}
        <div class="rounded-2xl min-h-[200px] flex justify-center ">
            <div class="text-center ">
                <a href="/artists/{artist.slug}" class="text-blue-500 hover:text-blue-700">
                    <img src={artist.image} alt="" class="max-w-[150px] mx-auto">
                </a>
                <a href="/artists/{artist.slug}" class="text-gray-700 hover:text-blue-700">
                    <p class="text-2xl">{artist.name}</p>
                </a>
            </div>
        </div>
         
    {/each}
</div>

<script>
    import data from '../artists.js'
</script>