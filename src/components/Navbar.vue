<template>
    <nav>
        <v-toolbar app flat>
            <v-toolbar-side-icon @click="toggleDrawer()" class="grey--text"></v-toolbar-side-icon>
            <v-toolbar-title class="text-uppercase grey--text">
                <span class="font-weight-light">Todo</span>
                <span>Ninja</span>
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn flat color="grey">
                <span>Sign Out</span>
                <v-icon right>exit_to_app</v-icon>
            </v-btn>
        </v-toolbar>
        <v-navigation-drawer v-model="drawer" app class="indigo">
            <p>Test</p>
        </v-navigation-drawer>
    </nav>
</template>

<script>
export default {
    data() {
        return {
            drawer: false
        }
    },
    methods: {
        toggleDrawer() {
            this.drawer = !this.drawer;
        }
    }
}
</script>

<style>

</style>
