<template>
<div id="app">
    <div class="container text-center p-2">
        <h1 class="display-5">SVG Interactivity</h1>
        <p>
            Las imágenes SVG pueden adaptarse a las acciones del usuario. SVG admite eventos de puntero, eventos de teclado y eventos de documentos. Considere el siguiente ejemplo.</p>
    <svgContainer  class="mt-5"/>

    </div>
</div>
</template>
<script>
import svgContainer from './components/svgContainer.vue'
export default {
    name: 'App',
    components: {
        svgContainer
    }
}
</script>
 