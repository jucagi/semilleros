<script setup>

const props = defineProps({
    programa: Object	
});

</script>





<template>

<!-- {
        nombre: "Licenciatura en Ciencias Sociales",
        semilleros: [
            "SIC",
            "Los Nadie"
        ],
        cantIntegrante: "60",
        cantProyectos: 10
    } -->

    <Card>
        <template #title>{{ programa.nombre }}</template>
        <template #content>
            <h3>Semilleros</h3>
            <p class="m-0">
                {{ programa.semilleros }}
            </p>
            <h3>Integrantes</h3>
            <p class="m-0">
                {{ programa.cantIntegrantes }}
            </p>
            <h3>Integrantes</h3>
            <p class="m-0">
                {{ programa.cantIntegrantes }}
            </p>
        </template>
    </Card>

</template>