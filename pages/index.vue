<template>
  <div>
    <Navbar />
    <heroHeader />
    <card />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import heroHeader from "@/components/heroHeader.vue";
import card from "@/components/card.vue";

export default {
  components: {
    Navbar,
    heroHeader,
    card,
  },
};
</script>
   
