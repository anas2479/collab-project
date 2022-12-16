
<div class="rounded-2xl w-[250px] min-h-[200px] flex justify-center ">
    <div class="text-center ">
        <img src={img} alt="" class="max-w-[150px] mx-auto">
        <p class="text-2xl">{title}</p>
        <p class="text-sm text-gray-600">{description}</p>
    </div>
</div>

<script>
    export let title = 'Card Link';
    export let description = 'This is a simple card';
    export let img = '';
</script>