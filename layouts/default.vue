<template>
    <div>
        <navbarComp />
        <slot />
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import navbarComp from '../components/navigations/navbarComp.vue'
export default defineComponent({
    components: {
        navbarComp
    }
})
</script>
