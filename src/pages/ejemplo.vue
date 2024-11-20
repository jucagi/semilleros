<script setup>

const arregloDeProgramas = [
    {
        nombre: "Licenciatura en Informática",
        semilleros: [
            "Avi",
            "Bimadino",
            "Lab de IA"
        ],
        cantIntegrante: "15",
        cantProyectos: 10
    },
    {
        nombre: "Licenciatura en Ciencias Sociales",
        semilleros: [
            "SIC",
            "Los Nadie"
        ],
        cantIntegrante: "60",
        cantProyectos: 10
    }
]

</script>

<template>
    <EjemploComp v-for="programaActual in arregloDeProgramas"  :programa="programaActual" />   

    <!-- <EjemploComp :programa="arregloDeProgramas[0]" />
    <EjemploComp :programa="arregloDeProgramas[1]" /> -->
</template>