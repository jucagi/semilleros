<script setup>
import semillerosJson from "../data/Semillero_LosNadie.json";

const integrantes = semillerosJson[0].integrantes
cont titulo = props.semillero.integrantes.estudiantes.length + " Estudiantes"
// const integrantes = {
//     estudiantes: [
//         "Juan",
//         "Jose",
//         "Andres"
//     ],
//     docentes: [
//         "Isabel C.",
//         "Linda"
//     ],
//     Coordinador: "Juan Carlos",
//     Asesor: "Julian" 
// }

</script>

<template>
    <JmIntegrantes :integrantes="integrantes" />
</template>

