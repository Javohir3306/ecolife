<template>
  <div>
    <!-- havbar -->
    <div class="bg-grey w-100pr h-90px"></div>
    <br><br>
    <!--responsive 1 -->
   <div class="fit row justify-around">
      <div class=" md w-45pr mobile-hide">
        <Persinal/>
      </div>
      <div class=" md w-35pr q-mt-xl">
        <Totalpej/>
      </div>
   </div>
   <!--responsive 2 -->
    <div>
      <div class=" justify-around  row  xs w-100pr ">
        <div class="w-90pr">
          <Persinal/>
        </div>
      </div>
      <div class="row justify-around xs w-100pr q-mt-xl">
          <Totalpej/>
      </div>
    </div>
    <!--responsive 3 -->
    <div class="fit row justify-around" >
      <div class=" sm w-45pr mobile-hide">
        <Persinal/>
      </div>
      <div class=" sm w-40pr q-mt-xl">
        <Totalpej/>
      </div>
    </div>
    <br><br>
    <!-- futer -->
    <div class="h-400px bg-grey w-100pr">

    </div>
  </div>
</template>

<script>
import Persinal from 'src/components/persinal.vue';
import Totalpej from 'src/components/Totalpej.vue';
export default {
    components: { Persinal, Totalpej }
}
</script>

<style>

</style>
