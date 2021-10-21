<template>
  <div>
    <Navbar />
    <heroHeader />
    <card />
    <mainFooter />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import heroHeader from "@/components/heroHeader.vue";
import card from "@/components/card.vue";
import mainFooter from "@/components/mainFooter.vue";


export default {
  components: {
    Navbar,
    heroHeader,
    card,
    mainFooter,
  },
};
</script>
   
