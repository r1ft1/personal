<script lang="ts">
  import sticker from "$lib/assets/sticker.svg";
  import pic from "$lib/assets/pic.jpg";
</script>

<div
  class="overflow-y-scroll xl:flex xl:justify-around xl:items-center bg-[#FEEDF4] xl:overflow-auto h-svh xl:h-screen snap-mandatory snap-y"
>
  <div class=" flex-col h-svh xl:h-full flex items-center py-8 snap-center">
    <!-- <div class="flex py-4 flex-col items-center"> -->
    <!--   <svg -->
    <!--     xmlns="http://www.w3.org/2000/svg" -->
    <!--     height="24px" -->
    <!--     viewBox="0 -960 960 960" -->
    <!--     width="24px" -->
    <!--     fill="#000000" -->
    <!--     ><path -->
    <!--       d="M450-180v-485.08L222.15-437.23 180-480l300-300 300 300-42.15 42.77L510-665.08V-180h-60Z" -->
    <!--     /></svg -->
    <!--   > -->
    <!--   <p>contact me</p> -->
    <!-- </div> -->
    <!---->
    <div
      class="flex flex-col items-center w-full h-1/2 mt-auto mb-auto justify-center gap-4"
    >
      <img class=" object-cover" alt="Oat Mocha Logo" src={sticker} />
      <p>website developer - leeds, UK</p>

      <p>oatmochadigital@gmail.com - Contact me!</p>
    </div>
    <div class="flex flex-col xl:hidden items-center">
      <p class="">about me</p>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        height="24px"
        viewBox="0 -960 960 960"
        width="24px"
        fill="#000000"
        ><path
          d="M450-780v485.08L222.15-522.77 180-480l300 300 300-300-42.15-42.77L510-294.92V-780h-60Z"
        /></svg
      >
    </div>
  </div>

  <div
    class="bg-[#FEEDF4] flex-col gap-4 h-screen xl:h-1/4 xl:w-1/4 flex snap-center items-start justify-center px-4 py-8"
  >
    <p>about me</p>
    <p class="text-md">
      James - website creation and hosting for small businesses in north
      yorkshire
    </p>
    <div class="object-cover xl:object-contain w-full flex gap-2">
      <img src={pic} alt="Pic of the Author and Dog" />
      <div class="flex flex-col justify-between"></div>
    </div>
    <p>Billy (dog)</p>
  </div>
</div>
