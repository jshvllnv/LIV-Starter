<script setup>
import Container from "../../Components/Container.vue";
import Title from "../../Components/Title.vue";
import TextLink from "../../Components/TextLink.vue";
</script>

<template>
    <Container>
        <div class="mb-3 text-center">
            <Title>Register a new account</Title>
            <p>
                Already have an account?
                <TextLink routeName="home" label="Login"></TextLink>
            </p>
        </div>
    </Container>
</template>
