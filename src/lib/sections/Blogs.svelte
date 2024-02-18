<script>
    import vecBG2 from '../images/vecbg2.png';
    import person1 from '../images/person1.png';
    import person2 from '../images/person2.png';
    import BlogLarge from '../components/BlogLarge.svelte';
    import BlogSmall from '../components/BlogSmall.svelte';

</script>


<section class="text-[#215476] h-[123vh] bg-white bg-fill relative " style="background-image:url('{vecBG2}');">
    <h1 class="text-7xl text-black ml-20 relative mb-10 ">&#8203;</h1>
    <h1 class="text-7xl text-white ml-20 mb-10">Recent Blogs</h1>
    <div class="flex flex-row gap-8 flex-wrap justify-center ">
        <BlogLarge/>
        <div class="flex flex-row lg:flex-col gap-4 flex-wrap items-center justify-center">
        <BlogSmall image={person1} name="Melissa Brown" year="08 Jan 2024" title="The Unexpected Dangers of Gum Disease" text="Gum disease is common and unpleasant, but, according to a growing body of evidence, it could but but, according to a growing body of common and unpleasant, but, according to a growing evidence... "/>
        <BlogSmall image={person2} name="Melissa Brown" year="08 Jan 2024" title="The Unexpected Dangers of Gum Disease" text="Gum disease is common and unpleasant, but, according to a growing body of evidence, it could but but, according to a growing body of common and unpleasant, but, according to a growing evidence..."/>
        <BlogSmall image={person1} name="Melissa Brown" year="08 Jan 2024" title="The Unexpected Dangers of Gum Disease" text="Gum disease is common and unpleasant, but, according to a growing body of evidence, it could but but, according to a growing body of common and unpleasant, but, according to a growing evidence..."/>
        
    </div>
    </div>
</section>

