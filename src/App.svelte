<script>
  import otakuBG from "./assets/otakubg.svg"
  import comicBG from "./assets/bg.webp"
</script>
<div class="w-screen h-screen flex flex-col items-center justify-center">
    <img src = {otakuBG} class="md:h-screen w-screen object-cover top-0 left-0 z-10" alt="Otaku logo">
    <img src = {comicBG} class="h-screen w-screen object-cover fixed top-0 left-0 z-0 brightness-[30%]" alt="Cominc BG">
</div>

<slot />

<style>

</style>