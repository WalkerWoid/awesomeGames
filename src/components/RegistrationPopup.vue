<script setup>
  import {ref} from "vue";

  let isPopupVisible = ref(false)
  const body = ref(document.querySelector("body"))
  const changePopupVisibility = () => {
    isPopupVisible.value = !isPopupVisible.value
    body.value.classList.toggle('body_hidden')
  }
</script>

<template>
  <button class="popup-btn main-btn" @click="changePopupVisibility">Registration <br> Now</button>

  <div class="popup" v-show="isPopupVisible">
    <div class="popup__shadow" @click="changePopupVisibility"></div>

    <div class="popup__container">
      <h2 class="section__header">CREATE A FREE ACCOUNT NOW</h2>

      <form action="#">
        <label><input type="text" placeholder="Firstname"></label>
        <label><input type="text" placeholder="Lastname"></label>
        <label><input type="email" placeholder="Email"></label>

        <label class="privacy">
          <input type="checkbox" name="privacy" value="agree-with-privacy">
          <span>I accept the <a href="#">Privacy Policy</a></span>
        </label>

        <button type="submit" class="main-btn" @click="changePopupVisibility">Registration</button>
      </form>
    </div>
  </div>
</template>

<style scoped>
  .popup-btn {
    cursor: pointer;
    position: fixed;
    top: 20px;
    right: 20px;
    z-index: 5;
  }
  .popup {
    position: fixed;
    inset: 0;
    z-index: 4;
    display: flex;
    justify-content: center;
    align-content: center;
    transition-duration: .4s;
  }
  .popup__shadow {
    background-color: var(--dark-blue);
    opacity: .5;
    z-index: 3;
    position: absolute;
    inset: 0;
  }
  .popup__container {
    align-self: center;
    background-color: var(--dark-blue);
    padding: 20px;
    border-radius: var(--main-radius);
    display: flex;
    flex-direction: column;
    gap: 12px;
    z-index: 3;
  }
  .popup__container form {
    display: flex;
    flex-direction: column;
    gap: 12px;
  }
</style>