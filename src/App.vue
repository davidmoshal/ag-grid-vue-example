<template>
    <div id="app"></div>
</template>

<script>
    import Vue from "vue";

    import "../node_modules/ag-grid/dist/styles/ag-grid.css"
    import "../node_modules/ag-grid/dist/styles/theme-fresh.css"
    // only needed if you're using enterprise features
    import "ag-grid-enterprise/main";

    import RichGridExample from './rich-grid-example/RichGridExample.vue'
    import DynamicComponentExample from './dynamic-component-example/DynamicComponentExample.vue'
    import EditorComponentExample from './editor-component-example/EditorComponentExample.vue'
    import PinnedRowExample from './pinned-row-example/PinnedRowExample.vue'
    import FullWidthRowExample from './full-width-example/FullWidthExample.vue'
    import GroupedRowExample from './grouped-row-example/GroupedRowExample.vue'
    import FilterExample from './filter-example/FilterExample.vue'

    export default {
        components: {
            'rich-grid-example': RichGridExample,
            'dynamic-components-example': DynamicComponentExample,
            'editor-components-example': EditorComponentExample,
            'pinned-row-example': PinnedRowExample,
            'full-width-row-example': FullWidthRowExample,
            'grouped-row-example': GroupedRowExample,
            'filter-example': FilterExample
        }
    }
</script>

<style>
</style>
