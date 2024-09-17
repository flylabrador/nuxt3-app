<template>
    <button @click="handleClick">
      <slot></slot>
    </button>
  </template>
  
  <script setup>
  function handleClick() {
    alert('按钮被点击了！')
  }
  </script>
  