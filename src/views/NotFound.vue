<template>
    <div>
        <h1>Not Found</h1>
        <p>Oops we couldn't find the page. try going
            <router-link :to="{ name: 'home' }">Home</router-link>
        </p>
    </div>
</template>