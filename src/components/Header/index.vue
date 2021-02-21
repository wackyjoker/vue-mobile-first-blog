<template>
    <header>
        <nav>
            <li>{{msg}}</li>
            <li>2</li>
            <li>3</li>
            <li>4</li>
        </nav>
    </header>
</template>

<script lang="ts">
    import { Options, Vue } from "vue-class-component";

    @Options({
        props: {
            msg: String
        }
    })
    export default class Header extends Vue {
        msg!: string;
    }
    </script>

<style  lang="scss" scoped>
    @import 'index.scss';
    </style>