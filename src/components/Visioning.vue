<template>
    <div class="box">
      <div class="box-header">
        <slot name="header"></slot>
      </div>
      <div class="box-body">
        <slot name="body"></slot>
      </div>
      <div class="box-footer">
        <slot name="footer"></slot>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Growth'
  }
  </script>
  
  <style scoped>
  .box {
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  .box-header {
    background-color: #f0f0f0;
    padding: 10px;
    border-bottom: 1px solid #ddd;
  }
  
  .box-body {
    padding: 20px;
  }
  
  .box-footer {
    background-color: #f0f0f0;
    padding: 10px;
    border-top: 1px solid #ddd;
  }
  </style>