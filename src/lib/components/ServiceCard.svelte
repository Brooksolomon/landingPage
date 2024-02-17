<script>
    export let vector
    export let image
    export let title
    export let desc
</script>
<div class="flex flex-col items-center">
<div class="relative mt-10">
    <img src="{image}" class="absolute inset-0  object-cover w-full z-1" />
        <img src="{vector}">
</div>
    <h1 class="text-xl text-white mt-6">{title}</h1>
    <p class="w-80 text-white mt-4">{desc}</p>
</div>