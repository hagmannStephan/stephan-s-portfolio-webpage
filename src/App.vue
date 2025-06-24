<script setup lang="ts">
  const navigateToExample = () => {
    window.location.href = 'https://example.com'
  }
</script>
<template>
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <p>Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos.</p>
  <div class="container area">
    <p>Text in seperated area</p>
  </div>
  <a href="https://example.com" target="_blank" rel="noopener">This is a link</a>
  <p>Lorem ipsum dolor sit amet consectetur adipiscing elit. Ut hendrerit semper vel class aptent taciti <a href="https://example.com" target="_blank" rel="noopener">inline link</a> sociosqu.</p>
  <br>
  <button @click="navigateToExample">This is a button</button>
</template>
