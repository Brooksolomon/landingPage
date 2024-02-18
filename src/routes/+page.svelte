<script>
	import smile from '../lib/images/smile.png';
	import smileBG from '../lib/images/smilebg.png';
	import vecBG from '../lib/images/vecbg.png';
	import i1 from '../lib/images/i1.png';
	import v1 from '../lib/images/v1.png';
	import i2 from '../lib/images/i2.png';
	import v2 from '../lib/images/v2.png';
	import i3 from '../lib/images/i3.png';
	import v3 from '../lib/images/v3.png';
	import i4 from '../lib/images/i4.png';
	import v4 from '../lib/images/v4.png';
	import ServiceCard from '../lib/components/ServiceCard.svelte';
	import Testimonials from '../lib/sections/Testimonials.svelte';
	import Blogs from '../lib/sections/Blogs.svelte';
	import MapContact from '../lib/sections/Map&Contact.svelte';
	import Footer from '../lib/sections/Footer.svelte'
</script>

<div class="relative bg-white">
	<section
		id="about-us"
		class=" bg-white inset-0 flex flex-col lg:flex-row py-36 mb-[-20rem] lg:mb-[-20rem]"
	>
		<div class=" flex-[0.5]">
			<h1 class="text-7xl ml-[4vw] md:mt-70 text-[#215476]">
				A Reason<br />
				<span class="text-8xl text-[#40a2e3]">to Smile</span>
			</h1>
			<br />
			<p class="ml-[4vw]">
				Capitalize on low hanging fruit to identify a ballpark value added activity to beta test.
				Override the digital divide with additional click throughs from DevOps. with additional
				click throughs fruit to identify
			</p>
			<div class="flex flex-wrap flex-row ml-[4vw] gap-8 mt-4">
				<button class="btn bg-[#215476] text-white w-[80vw] md:w-[40vw] lg:w-[20vw] h-16 text-xl hover:bg-[#40a2e3]"
					>Our Services</button
				>
				<button class="btn bg-[#215476] text-white w-[80vw] md:w-[40vw] lg:w-[20vw] h-16 text-xl hover:bg-[#40a2e3]"
					>Book appointemnt</button
				>
			</div>
		</div>


		<div class="  flex-[0.5] 400 m-5 flex flex-col items-center">
			<img
				src={smileBG}
				class=" w-[30rem] lg:w-[30rem] mb-[-90%] md:mb-[-60%] lg:mb-[-90%] xl:mb-[-60%]"
				alt=""
			/>
			<img src={smile} class=" w-[30rem] mr-[5rem] lg:w-[40rem]" alt="" />
		</div>
	</section>

	<section
		style="background-image:url('{vecBG}') ;"
		class="bg-cover relative z-20 "
	>
		<h1 class="text-7xl text-black ml-[2vw] relative mb-10">&#8203;</h1>
		<h1 class="text-7xl text-white ml-[10vw]  relative mb-10 mt-32 w-[80vw]">Our Services</h1>
		<p class="text-white ml-20 w-[80vw] mb-10">
			Seamlessly visualize quality intellectual capital without superior collaboration and
			idea-sharing. Holistically pontificate installed base portals after maintainable products.
		</p>
		<div class="flex flex-wrap flex-row gap-10 lg:gap-28 justify-center">
			<ServiceCard
				image={i1}
				vector={v1}
				title="General Dentistry"
				desc="Iterative approaches to corporate strategy foster collaborative thinking further value."
			/>
			<ServiceCard
				image={i2}
				vector={v2}
				title="Whitening"
				desc="Leverage agile frameworks to provide a robust synopsis for high level overviews"
			/>
			<ServiceCard
				image={i3}
				vector={v3}
				title="Root Canels"
				desc="Iterative approaches to corporate strategy foster collaborative thinking further value."
			/>
			<ServiceCard
				image={i4}
				vector={v4}
				title="Dental Care for Seniors"
				desc="Leverage agile frameworks to provide a robust synopsis for high level overviews."
			/>
		</div>
		<button
			class="btn bg-white text-[#215476] w-[50vw] md:w-[30] lg:w-[20vw] h-16 text-xl ml-[20vw] md:ml-[22vw] lg:ml-[40vw] mt-32 lg:mb-96 hover:bg-[#40a2e3] hover:text-white"
			>Veiw all Services</button
		>
	</section>
	<Testimonials/>
	<Blogs/>
	<MapContact/>
	<Footer/>

	
</div>