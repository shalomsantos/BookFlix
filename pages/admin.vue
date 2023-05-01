<template>
    <v-card>
        <v-layout>
            <v-navigation-drawer
              expand-on-hover
              rail>
              <v-list>
                <v-list-item
                  prepend-avatar="https://randomuser.me/api/portraits/women/85.jpg"
                  title="Sandra Adams"
                  subtitle="sandra_a88@gmailcom"
                ></v-list-item>
              </v-list>
              <v-divider></v-divider>
              <v-list density="compact" nav>
                <v-list-item  title="Central" value="Central"></v-list-item>
                <v-list-item  title="Volume 1" value="Volume 1"></v-list-item>
                <v-list-item  title="Volume 2" value="Volume 2"></v-list-item>
                <v-list-item  title="Volume 3" value="Volume 3"></v-list-item>
              </v-list>
            </v-navigation-drawer>
            <v-app-bar title="Application bar"></v-app-bar>
              <v-main style="min-height: 300px;">
              </v-main>
        </v-layout>
    </v-card>
</template>