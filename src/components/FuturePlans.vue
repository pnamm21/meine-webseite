<template>
    <div class="future-container">
        <h3>Zukunftspläne</h3>
        <ol class="future-goals">
            <li>Weiterführende Kenntnisse in Backend-Technologien (z. B. Node.js, Express)</li>
            <li>Integration von Datenbanken (z. B. MongoDB, MySQL)</li>
            <li>Optimierung und Skalierung von Web-Anwendungen</li>
            <li>Entwicklung mobiler Apps</li>
        </ol>
    </div>
</template>

<script>
export default {
    name: "FuturePlans"
};
</script>

<style>
.future-container {
    background-color: #e3f2fd;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.future-goals {
    list-style: decimal;
    padding-left: 20px;
    line-height: 1.8;
}

.future-goals li {
    margin-bottom: 10px;
    color: #0d47a1;
}
</style>
