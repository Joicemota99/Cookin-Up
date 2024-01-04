<script lang="ts">
import type ICategoria from '@/interfaces/ICategoria';

export default {
    props:{
        categoria: {type: Object as PropType<ICategorias>, required:true}
    }
}
</script>

<template>
    {{ categoria.nome }}
    {{ categoria.imagem }}
</template>