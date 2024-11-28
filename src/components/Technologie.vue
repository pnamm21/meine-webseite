<template>
    <div class="technology-container">
      <h3>Technologien</h3>
      <ul class="technology-list">
        <li><strong>Programmiersprachen:</strong> JavaScript, C#</li>
        <li><strong>Tools:</strong> Git, Visual Studio Code</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: "Technologie",
  };
  </script>
  
  <style scoped>
  .technology-container {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  .technology-list {
    list-style: none;
    padding: 0;
  }
  .technology-list li {
    margin-bottom: 10px;
    line-height: 1.6;
  }
  </style>
  