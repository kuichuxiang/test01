<template>
    <div>
        <router-link to="/a">aaaaaaaaa</router-link>
        <router-link to="/b">bbbbbbbbb</router-link>

        <router-view></router-view>

        <keep-alive><router-view></router-view></keep-alive>
    </div>
</template>
