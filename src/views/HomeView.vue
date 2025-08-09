<template>
    <h1>Home Page</h1>
    <p>Welcome to the home page of the application.</p>

    <nav>
        <router-link to="/home">Go to Home</router-link>
        <router-link to="/about">Go to About</router-link>
    </nav>
    <main>
        <router-view />
    </main>
</template>

<script setup>
</script>