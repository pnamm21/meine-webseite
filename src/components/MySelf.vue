<template>
    <div class="my-self">
        <h2>Über mich</h2>
        <h3>Herzlich willkomen!</h3>
        <p>
            Hallo, ich bin Pham. Ich bin ein Entwickler und liebe es, mit
            modernen Technologien zu arbeiten.
        </p>
    </div>
</template>

<script>
export default {
    name: "MySelf",
};
</script>

<style scoped>
.my-self {
    flex: 1;
    background-color: #f4f4f4;
    padding: 20px;
    height: 150px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.my-self h2 {
    color: #333;
    font-size: 24px;
    margin-bottom: 10px;
}

.my-self p {
    font-size: 16px;
    line-height: 1.6;
    color: #555;
}
</style>