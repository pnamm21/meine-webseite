<template>
    <div class="module-container">
        <h3>topfact6 JobServer Module</h3>
        <ul class="module-list">
            <li>
                <span>FileReader</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 95%;"></div>
                </div>
            </li>
            <li>
                <span>XMLReader</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 90%;"></div>
                </div>
            </li>
            <li>
                <span>ZUGFeRD Reader</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 70%;"></div>
                </div>
            </li>
            <li>
                <span>Paperworks</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 80%;"></div>
                </div>
            </li>
            <li>
                <span>SDSync</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 100%;"></div>
                </div>
            </li>
            <li>
                <span>PreSelect 2.0</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 80%;"></div>
                </div>
            </li>
            <li>
                <span>Database Agent</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 100%;"></div>
                </div>
            </li>
            <li>
                <span>FileCleaner</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 100%;"></div>
                </div>
            </li>
            <li>
                <span>GWC</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 70%;"></div>
                </div>
            </li>
            <li>
                <span>Formrecognizer</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 50%;"></div>
                </div>
            </li>
            <li>
                <span>Version Control</span>
                <div class="progress-bar">
                    <div class="progress" style="width: 100%;"></div>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "Topfact6Module"
};
</script>

<style scoped>
.module-container {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.module-list {
    list-style: none;
    padding: 0;
    margin: 0;
}

.module-list li {
    margin-bottom: 15px;
}

.progress-bar {
    width: 100%;
    background-color: #eaeaea;
    border-radius: 5px;
    overflow: hidden;
    height: 10px;
    margin-top: 5px;
}

.progress {
    height: 100%;
    background-color: #4caf50;
}
</style>
