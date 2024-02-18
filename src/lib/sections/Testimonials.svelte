<script>
    import TestimonialCard from "../components/TestimonialCard.svelte";
    import person1 from '../images/person1.png';
    import person2 from '../images/person2.png';
</script>


<section class="flex flex-col items-center justify-center mt-[-60px] ">
    <h1 class="text-6xl text-[#215476] mt-32 mb-12">Happy Patients</h1>
    <div class="flex flex-col gap-10 flex-wrap items-center justify-center">
    <div class="flex flex-row  lg:gap-36 flex-wrap items-center justify-center">
    <TestimonialCard image={person1} name="Melissa Brown" text="Organically grow the holistic world view of disruptive innovation via better workplace."/>
    <TestimonialCard image={person2} name="Melissa Brown" text="Organically grow the holistic world view of disruptive innovation via better workplace."/>
        </div>
        <div class="flex flex-row ;g:gap-36 flex-wrap items-center justify-center lg:ml-[4vw]">
    <TestimonialCard image={person2} name="Melissa Brown" text="Organically grow the holistic world view of disruptive innovation via better workplace."/>
    <TestimonialCard image={person1} name="Melissa Brown" text="Organically grow the holistic world view of disruptive innovation via better workplace."/>
    </div>   
    </div>
    <button
    class="btn bg-[#215476] w-80 h-16 text-xl mt-32 mb-36 hover:bg-[#40a2e3] text-white"
    >More testimonals</button
>
    </section>