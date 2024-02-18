<script>
    import {Phone, Envelope} from "phosphor-svelte"
</script>
<footer class="footer p-10 bg-[#215476]  text-white items-center"> 
    <nav>
      <h6 class="footer-title text-xl">Links</h6> 
      <a class="link link-hover">FAQ</a>
      <a class="link link-hover">Blog</a>
      <a class="link link-hover">Pricing</a>
      <a class="link link-hover">Insurance</a>
      <a class="link link-hover">Partners</a>
      <a class="link link-hover">Careers</a>
    </nav> 
    <aside class="text-2xl justify-center flex flex-col flex-wrap items-center">
      <h1 ><b>PRIVATE</b>DENTISTRY</h1>
      <h1>AWARDS 2022</h1>
      <div class="divider divider-info"></div> 
      <h1>FINALIST</h1>
      <h1>BEST TEAM</h1>
    </aside>
    <nav>
      <h6 class="footer-title">CLINIC HOURS</h6> 
      <a class="link link-hover">Monday &nbsp;&nbsp; 8am - 6pm</a>
      <a class="link link-hover">Tuesday &nbsp;&nbsp; 8am - 6pm</a>
      <a class="link link-hover">Wednesday &nbsp;&nbsp; 8am - 4pm</a>
      <a class="link link-hover">Thursday &nbsp;&nbsp; 8am - 6pm</a>
      <a class="link link-hover">Firday &nbsp;&nbsp; 10am - 4pm</a>
      <a class="link link-hover">Saturday &nbsp;&nbsp; 10am - 12pm</a>
      <a class="link link-hover">Sunday &nbsp;&nbsp; closed</a>
    </nav> 
    <nav>
      <h6 class="footer-title">CONTACT US</h6> 
      <p class="link link-hover w-60">We are a friendly team of dentists, hygienists and receptionists who work together to ensure you receive the best treatment you require.</p>
      <p class="link link-hover">245 E 63rd St #110</p>
      <p class="link link-hover">New York, NY 10065</p>
      <br>
      <button
      class="btn bg-white text-[#215476]  text-l  hover:bg-[#40a2e3] hover:text-white w-40"
      >Book Now</button
  >
    </nav>
  </footer>
  <!-- <div class="divider bg-[#215476] m-0 divider-info"></div> -->
  <footer class="footer items-center p-4  bg-[#215476] text-white pb-10">
    <aside class="items-center grid-flow-col pl-20">
      <p>© 2024 - All right reserved</p>
    </aside> 
    <nav class="flow-col gap-4 md:place-self-center md:justify-self-end pr-20 flex-wrap">
        <Phone size={22}/> <p class="">(514)-206-886</p> 
        <Envelope size={22}/> <p>reception@denticare.com</p>
    </nav>
  </footer>