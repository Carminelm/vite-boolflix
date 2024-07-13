<script>

import AppHeader from './components/AppHeader.vue';
import { store } from './store.js';
import axios from 'axios';

export default {
    components: {
        AppHeader,

    },
    data() {
        return {
            store,
        }
    },
    methods:{

}


}

</script>

<template lang="">

    <div>
        <AppHeader @search="searchMovie" />
        <AppMain />
    </div>

</template>

<style lang="scss">

    @import './styles/generals.scss';
    @import '../node_modules/bootstrap/scss/bootstrap';

</style>
