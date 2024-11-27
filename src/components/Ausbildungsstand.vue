<template>
    <div class="education-container">
      <h3>Ausbildungsstand</h3>
      <ul class="education-list">
        <li>
          <strong>Grundlagen in Webentwicklung:</strong>
          <span>HTML, CSS, JavaScript</span>
        </li>
        <li>
          <strong>Frameworks gelernt:</strong>
          <span>Vue.js, Bootstrap</span>
        </li>
        <li>
          <strong>Aktueller Projekt:</strong>
          <span>Erstellung von Web-Komponenten</span>
        </li>
      </ul>
      <button class="view-pdf-button" @click="openPDF">Präsentation anschauen</button>
    </div>
  </template>
  
  <script>
  export default {
    name: "EducationStatus",
    methods: {
      openPDF() {
        window.open("Meine Ausbildung.pdf", "_blank");
      },
    },
  };
  </script>
  
  <style>
  .education-container {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  .education-list {
    list-style: none;
    padding: 0;
  }
  
  .education-list li {
    margin-bottom: 15px;
    line-height: 1.6;
  }
  
  .education-list strong {
    color: #333;
  }
  
  .view-pdf-button {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 14px;
    transition: background-color 0.3s ease;
  }
  
  .view-pdf-button:hover {
    background-color: #0056b3;
  }
  </style>
  