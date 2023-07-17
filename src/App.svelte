<script>
    import CC from "./lib/CenterComponent.svelte"
    import comicBG from "./assets/bg.webp"
</script>
<div class="w-screen h-screen flex flex-col items-center justify-center">

    <CC/>


    <img src = {comicBG} class="h-screen w-screen object-cover fixed top-0 left-0 z-0 fadeinBGAnim" alt="Cominc BG">
</div>

<slot />

<style>


    @keyframes fadeinBG {
        0%{
            filter: brightness(100%);
        }
        100%{
            filter: brightness(30%);
        }
    }

    .fadeinBGAnim{
        animation: fadeinBG ease 300ms;
        animation-iteration-count: 1;
        animation-fill-mode: forwards;
    }



</style>