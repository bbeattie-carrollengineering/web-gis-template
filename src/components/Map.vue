<script setup>

import "@arcgis/map-components/dist/components/arcgis-map";
import "@arcgis/map-components/dist/components/arcgis-placement";
import "@esri/calcite-components/dist/components/calcite-button";

function reloadPage() {
    location.reload();
}

</script>

<template>
    <arcgis-map basemap="gray" zoom="4" center="-92,40">
        <arcgis-placement position="bottom-right">
            <calcite-button @click="reloadPage()" round="" icon-start="reset" scale="l">Reload Page</calcite-button>
        </arcgis-placement>
    </arcgis-map>
</template>

<style scoped>

arcgis-map {
    width: 100%;
    height: 100%;
}

</style>