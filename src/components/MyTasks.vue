<template>
    <div class="tasks-container">
      <h3>Meine Aufgaben</h3>
      <p>Liste der Aufgaben oder Projekte, an denen ich arbeite:</p>
      <ul class="task-list">
        <li class="task-item">
          <input type="checkbox" id="task1" />
          <label for="task1">Entwicklung der Benutzeroberfläche für die Web-App</label>
        </li>
        <li class="task-item">
          <input type="checkbox" id="task2" />
          <label for="task2">Testen der neuen Features im System</label>
        </li>
        <li class="task-item">
          <input type="checkbox" id="task3" />
          <label for="task3">Dokumentation für das API-Projekt erstellen</label>
        </li>
        <li class="task-item">
          <input type="checkbox" id="task4" />
          <label for="task4">Code-Review der letzten Sprint-Aufgaben</label>
        </li>
        <li class="task-item">
          <input type="checkbox" id="task5" />
          <label for="task5">Optimierung der Performance der App</label>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: "MyTasks"
  };
  </script>
  
  <style scoped>
  .tasks-container {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    height: auto;
  }
  
  .tasks-container h3 {
    margin-top: 0;
    font-size: 24px;
    color: #333;
  }
  
  .tasks-container p {
    font-size: 16px;
    color: #666;
  }
  
  .task-list {
    list-style: none;
    padding: 0;
    margin: 20px 0 0;
  }
  
  .task-item {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
  }
  
  .task-item input[type="checkbox"] {
    margin-right: 10px;
    accent-color: #df4d4d;
  }
  
  .task-item label {
    font-size: 18px;
    color: #333;
    cursor: pointer;
  }
  
  .task-item input[type="checkbox"]:checked + label {
    text-decoration: line-through;
    color: #a8a8a8;
  }
  
  .task-item:hover {
    background-color: #f0f0f0;
    border-radius: 5px;
    padding: 5px;
    transition: background-color 0.3s ease;
  }
  
  @media (max-width: 768px) {
    .tasks-container {
      padding: 15px;
    }
  
    .task-list {
      margin: 10px 0;
    }
  
    .task-item label {
      font-size: 16px;
    }
  }
  </style>
  