<template>
  <div>
    <IntroBlog
      title="قائمة السور"
      info="فَإِذَا قَرَأْتَ الْقُرْآنَ فَاسْتَعِذْ بِاللَّهِ مِنَ الشَّيْطَانِ الرَّجِيمِ  (98) (النحل)"
    />
    
    <div class="w-4/5 mx-auto my-0 py-11">
      <h1 class="text-center text-basic-02 text-5xl font-black">المحتوى</h1>

      <div class="flex justify-end items-center ">
        <div class="z-30 cursor-pointer text-xl text-basic-02 flex items-center justify-between">
          <NuxtLink to="/" class=" bg-white flex items-center justify-center w-8 h-8 border border-basic-02 rounded-lg text-xl text-basic-02">
            <i class="fi fi-rr-angle-double-small-left w-5 h-5"></i>
          </NuxtLink>
        </div>
      </div>
    <Surah />
    </div>
  </div>
</template>

<script>
import Surah from '~/components/Surah.vue';
import IntroBlog from '../../components/blog/intro-blog.vue';
export default {
  components: {
    Surah,
    IntroBlog
},
  head(){
    return {
      title: "قائمة السور"
    }
  }
}
</script>