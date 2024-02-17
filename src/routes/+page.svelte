<script>
    import smile from '../lib/images/smile.png'
    import smileBG from  '../lib/images/smilebg.png'
    import vecBG from '../lib/images/vecbg.png'
    import i1 from '../lib/images/i1.png'
    import v1 from '../lib/images/v1.png'
    import i2 from '../lib/images/i2.png'
    import v2 from '../lib/images/v2.png'
    import i3 from '../lib/images/i3.png'
    import v3 from '../lib/images/v3.png'
    import i4 from '../lib/images/i4.png'
    import v4 from '../lib/images/v4.png'
    import ServiceCard from "../lib/components/ServiceCard.svelte";
</script>
<div class="relative">
<section id="about-us" class="bg-white inset-0" >
<div class="grid grid-cols-1 md:grid-cols-2 gap-80">
    <div>
        <h1 class="text-7xl ml-20 mt-60 md:mt-70 text-[#215476]">A Reason<br/>
        <span class="text-8xl text-[#40a2e3]">to Smile</span></h1>
        <br>
        <p class="ml-20">Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional click throughs from DevOps.
            with additional click throughs fruit to identify</p>
        <div class="flex flex-wrap flex-row ml-20 gap-8 mt-4">
            <button class="btn bg-[#215476] text-white w-80 h-16 text-xl hover:bg-[#40a2e3]">Our Services</button>
            <button class="btn bg-[#215476] text-white w-80 h-16 text-xl hover:bg-[#40a2e3]" >Book appointemnt</button>
        </div>
    </div>
    <div>
        <div class="relative mt-10  ">
            <img src="{smile}" class="absolute inset-0  object-cover w-3/4  " />
                <img src="{smileBG}" >
        </div>
    </div>

</div>
</section>
<section style="background-image:url('{vecBG}') ;" class="absolute inset-0 top-[300px]  bg-[length:2000px_1000px] ">
    <h1 class="text-7xl text-black ml-20 relative mb-10 ">&#8203;</h1>
    <h1 class="text-7xl text-white ml-20 relative mb-10 mt-32 ">Our Services</h1>
    <p class="text-white ml-20 w-[800px] mb-10">Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing. Holistically pontificate installed base portals after maintainable products.</p>
    <div class="flex flex-wrap flex-row gap-28 justify-center">
        <ServiceCard image={i1} vector={v1} title = "General Dentistry" desc="Iterative approaches to corporate strategy foster collaborative thinking further value."/>
        <ServiceCard image={i2} vector={v2} title= "Whitening" desc="Leverage agile frameworks to provide a robust synopsis for high level overviews"/>
        <ServiceCard image={i3} vector={v3} title = "Root Canels"  desc="Iterative approaches to corporate strategy foster collaborative thinking further value."/>
        <ServiceCard image={i4} vector={v4} title="Dental Care for Seniors" desc="Leverage agile frameworks to provide a robust synopsis for high level overviews."/>
    </div>
    <button class="btn bg-white text-[#215476] w-80 h-16 text-xl ml-[20vw] md:ml-[34vw] lg:ml-[40vw] mt-32 mb-36 hover:bg-[#40a2e3] hover:text-white">Veiw all Services</button>
</section>
<!-- <section class="flex justify-center">
    <h1 class="text-6xl text-[#215476] mt-10">Happy Patients</h1>
</section> -->
</div>