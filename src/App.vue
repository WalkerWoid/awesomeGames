<script setup>
import {onBeforeMount, onMounted, ref} from "vue";

  import Main from "@/components/Main.vue";
  import RegistrationPopup from "@/components/RegistrationPopup.vue";
  let isLoading = ref(false)
  let body = ref(document.querySelector('body'))

  onBeforeMount(() => {
    isLoading.value = true
  })
  onMounted(() => {
    setTimeout(() => {
      body.value.querySelector('.loader').style.display = 'none'
    }, 10)
  })
</script>

<template>
  <Main />
  <RegistrationPopup />
</template>