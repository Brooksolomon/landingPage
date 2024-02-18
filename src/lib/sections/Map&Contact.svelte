<script>
    import mapVector from '../images/mapVector.png'
    import ContactForm from '../components/ContactForm.svelte';

</script>



<section class="bg-white mb-20">
    <div class="flex flex-row flex-wrap  lg:gap-20 ml-10 justify-center">
        <div>
        <img src="{mapVector}" class=" w-[80vw] lg:w-[36vw] mb-[-42vh] lg:mb-[-56vh]">
        <div class="mask">
        <iframe src="https://www.google.com/maps/embed?pb=!1m17!1m12!1m3!1d3023.7849649837035!2d-73.98244792335261!3d40.72275003695649!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zNDDCsDQzJzIxLjkiTiA3M8KwNTgnNDcuNSJX!5e0!3m2!1sen!2set!4v1708265176549!5m2!1sen!2set"  style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="mask mask-hexagon-2 w-[80vw] lg:w-[36vw] h-[50vh]"></iframe>
        </div>
        </div>
        <ContactForm/>
    </div>
</section>
<style>
.mask{
-webkit-mask-image: url(../images/mapMask.png);
mask-image: url(../images/mapMask.png);
-webkit-mask-size: 100%;
mask-size: 100%;
-webkit-mask-repeat: no-repeat;
mask-repeat: no-repeat;  
}
</style>