<template>
    <div class="project-tracking-container">
      <h3>Projekttracking</h3>
      <ul class="project-list">
        <li><strong>Laufende Projekte:</strong> Kalender mit Erinnerungsfunktion</li>
        <li><strong>Abgeschlossene Projekte:</strong> Topfact6 Module Integration</li>
        <li><strong>Zukünftige Projekte:</strong> Automatisierte PDF-Generierung</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: "ProjektTracking",
  };
  </script>
  
  <style scoped>
  .project-tracking-container {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  .project-list {
    list-style: none;
    padding: 0;
  }
  .project-list li {
    margin-bottom: 10px;
    line-height: 1.6;
  }
  </style>
  