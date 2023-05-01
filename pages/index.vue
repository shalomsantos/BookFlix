<template>
    <v-sheet class="d-flex flex-column px-6 py-10 my-16 mx-auto elevation-10" width="400" rounded>
        <h1 class="text-center text-deep-purple-accent-4">Login BookFlix</h1>
        <div class="my-8">
            <v-text-field label="Nome" variant="underlined" hide-details class="mb-6"></v-text-field>
            <v-text-field label="Senha" variant="underlined" hide-details></v-text-field>
        </div>
        <v-btn variant="outlined" class="mb-4 bg-deep-purple-accent-4" rounded="md" to="/admin">
            Entrar
        </v-btn>
        <v-btn variant="outlined" class="bg-deep-purple-accent-4" rounded="md">
            Cadastrar
        </v-btn>
    </v-sheet>
</template>