<!--
CMatch by Alexander Abraham, a.k.a. "Angel Dollface".
Licensed under the MIT license.
-->

<template>

 <!--
  The main component uniting
  everything.
 -->
 <LineBreak/>
 <LineBreak/>
 <ColorMatch name="Color Match" />
 <FooterCog/>

</template>

<script>

// Importing the components and
// including them.
import ColorMatch from './components/ColorMatch.vue';
import LineBreak from './components/LineBreak.vue';
import FooterCog from './components/FooterCog.vue';
export default {
  name: 'App',
  components: {
    ColorMatch,
    LineBreak,
    FooterCog
  },
}
</script>