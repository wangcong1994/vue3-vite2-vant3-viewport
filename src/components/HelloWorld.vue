<template>
  <van-image :src="image" class="image"></van-image>
</template>

<script setup>
import image from "../assets/logo.png?url";
</script>

<style>
.image {
  font-size: 14px;
  width: 100px;
}
</style>
