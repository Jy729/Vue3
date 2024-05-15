<template>
    <div class="home">
        <header class="header">
            <h1>Hello World</h1>
        </header>
        <main class="content">
            <p>Sample testing</p>
            <p>Sample testing</p>
            <p>Sample testing</p>
        </main>
        <footer class="footer">
            <p>&copy; 2024</p>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'HomePage'
};
</script>

<style scoped>
.home {
    text-align: center;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    margin-top: 60px;
    padding: 20px;
}

.header {
    background-color: #41b883;
    color: white;
    padding: 20px 0;
}

.content {
    margin: 20px 0;
}

.footer {
    margin-top: 20px;
    font-size: 0.8em;
    color: #666;
}
</style>



