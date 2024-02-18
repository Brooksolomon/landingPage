<script>
    export let image
    export let name 
    export let text
</script>

<div class="flex flex-row gap-6 ">
    <img src="{image}">
    <div class="flex flex-col text-[#215476]">
        <p class="mt-6 w-[30vw] mb-2">{text}</p>
        <h1 class="font-bold">{name}</h1>
    </div>
</div>
