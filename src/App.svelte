<script>
  import otakuBG from "./assets/otakubg.svg"
  import comicBG from "./assets/bg.webp"
</script>
<div class="w-screen h-screen">
    <img src = {otakuBG} class="h-screen w-screen object-cover fixed top-0 left-0 z-10">
    <img src = {comicBG} class="h-screen w-screen object-cover fixed top-0 left-0 z-0 brightness-[30%]">
</div>

<slot />

<style>

</style>