<template>
    <div>
        <h1>Hola</h1>
        {{ message }}
    </div>
</template>

<script>
export default {
    props: ["message"],
    mounted() {
        console.log("Component mounted.");
    }
};
</script>
