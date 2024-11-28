<template>
    <div class="contact-container">
        <h2>Kontaktieren Sie mich</h2>
        <p>Sie können mich über folgende Plattformen erreichen:</p>
        <ul>
            <li>
                <a href="https://www.linkedin.com/in/deinprofil" target="_blank">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
            </li>
            <li>
                <a href="https://github.com/pnamm21/meine-webseite" target="_blank">
                    <i class="fab fa-github"></i> GitHub
                </a>
            </li>
            <li>
                <a href="mailto:ffam5004@gmail.com">
                    <i class="fas fa-envelope"></i> E-Mail
                </a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "SocialMedia",
};
</script>

<style>
.contact-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 10px;
    background-color: #f4f4f4;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
    font-size: 14px;
}

.contact-container h2 {
    margin-bottom: 10px;
}

.contact-container ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

.contact-container li {
    display: inline-block;
}

.contact-container a {
    text-decoration: none;
    color: #0073e6;
    font-size: 24px;
}

.contact-container a:hover {
    color: #005bb5;
}

.contact-container i {
    margin-right: 8px;
}
</style>