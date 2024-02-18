<script>
    import "../app.css";
    import Navbar from "../lib/components/Navbar.svelte";
    import {FacebookLogo, TwitterLogo, InstagramLogo, YoutubeLogo, House, Phone} from "phosphor-svelte"
  </script>
  <header class="footer bg-[#215476] text-base-content  ">
    <div class="flex flex-row ml-20">
    <p class="text-white p-2">Monday -Friday 8AM - 6PM</p>
    <span class="text-white ml-5 p-2">Request an appointemnt</span>
    </div>
    <div class="lg:flex hidden flex-row gap-4 md:place-self-center md:justify-self-end mr-32  text-[#215476]">
        <a class="p-2"><FacebookLogo size="{29}" weight="fill" color="white"/></a>
        <a class="p-2"><TwitterLogo size="{29}" weight="fill" color="white"/></a>
        <a class="p-2"><InstagramLogo size="{29}" weight="fill" color="white"/></a>
        <a class="p-2"><YoutubeLogo size="{29}" weight="fill" color="white"/></a>
        <a class="p-2"><House size="{29}" weight="fill" color="white"/></a>
        <span class="flex flex-row bg-[#40a2e3] p-2 ml-2"><Phone size="{29}" weight="fill" color="white"/>(514)-206-886</span>
    </div>
    
  </header>
  <Navbar/>
  <slot />

  <style>
    body{
      background-color: white;
    }
  </style>