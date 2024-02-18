<script>
    export let image
    export let name
    export let year
    export let title
    export let text
</script>

<div class="bg-white flex flex-row flex-wrap rounded-3xl p-2 w-[40vw] gap-4 justify-center h-48 overflow-hidden">
<div class="flex flex-col flex-wrap justify-center items-center">
    <img src='{image}' class="w-24">
    <p class="font-bold text-s">{name}</p>
    <p class="text-xs">{year}</p>
</div>
<div class="flex flex-col flex-wrap">
    <p class="font-bold text-xl hidden md:flex">{title}</p>
    <p  class="w-[30vw] hidden lg:flex ">{text}</p>

</div>  
</div>

