<template>
    <div>

    </div>
</template>
<script
import { "mapbox-config.js" } from "@vue/territorio_app_vue";
</script>
<style>
  body {
        margin: 0;
        padding: 0;
    }
    
    #map {
        position: absolute;
        top: 0;
        bottom: 0;
        width: 100%;
        margin-top: 40px;
    }
    
    .mapboxgl-popup-content {
        position: relative;
        border-radius: 10px!important;
        box-shadow: -4px 3px 3px rgba(0, 0, 0, 0.7)!important;
        padding: 15px 14px 6px !important;
        padding-left: 9px!important;
        pointer-events: auto;
    }
    
    #borrar,
    #enviar {
        width: 50px;
        height: 20px;
        margin-bottom: 8px;
        border-radius: 7px;
    }
</style>