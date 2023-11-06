<template>
  <h1>Main Page</h1>
  <button @click="handleClick">Coupon Get</button>
  <LazyCoupon v-if="show" />
</template>
<script setup>
const show = ref(false)

const handleClick = () => {
  show.value = true
}
</script>
