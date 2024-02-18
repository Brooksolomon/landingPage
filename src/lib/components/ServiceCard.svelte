<script>
    export let vector
    export let image
    export let title
    export let desc
</script>
<div class="flex flex-col items-center">
<div class="relative">
    <img src="{image}" class="absolute inset-0  object-cover w-[10vw] z-1" />
        <img src="{vector}" class="w-[10vw]">
</div>
    <h1 class="text-xl text-white mt-6">{title}</h1>
    <p class="w-80 text-white mt-4 hidden md:flex">{desc}</p>
</div>