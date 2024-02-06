<template>
 <v-app-bar height="80" color="#fef5f8" scroll-behavior="elevate" id="inspire">
    <v-img src="/1.png" class=""></v-img>
    <v-app-bar-title class="text-h4">Explore</v-app-bar-title>
    <v-spacer></v-spacer>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#6347f9" v-bind="props">Home +</v-btn>
        </template>
        <v-list>
            <v-list-item>
                <v-list-item-title>Home 1</v-list-item-title>
                <v-list-item-title>Home 2</v-list-item-title>
            </v-list-item>
        </v-list>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#6347f9" v-bind="props">Tours +</v-btn>
        </template>
        <v-list>
            <v-list-item>
                <v-list-item-title>Tour 1</v-list-item-title>
                <v-list-item-title>Tour 2</v-list-item-title>
                <v-list-item-title>Tour 2</v-list-item-title>
            </v-list-item>
        </v-list>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#6347f9" v-bind="props">Hotels</v-btn>
        </template>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#6347f9" v-bind="props">Pages +</v-btn>
        </template>
        <v-list>
            <v-list-item>
                <v-list-item-title>About</v-list-item-title>
                <v-list-item-title>Faq</v-list-item-title>
                <v-list-item-title>Team</v-list-item-title>
            </v-list-item>
        </v-list>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#6347f9" v-bind="props">Blog</v-btn>
        </template>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#6347f9" v-bind="props">Contact</v-btn>
        </template>
    </v-menu>
    <v-btn class="text-white  expl mr-8" color="white" size="x-large" veriant="flat" rounded="0">
        Get Exploration
    </v-btn>
 </v-app-bar>
</template>

<script>
export default {

}
</script>

<style scoped>
.expl {
    background-color: #6347f9;
    color: white;
}
</style>