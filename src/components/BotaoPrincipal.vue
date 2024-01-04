<script lang="ts">
export default {
    props: {
        texto: { type: String, required: true}
    }
}
</script>

<template>
     <button class="paragrafo-lg botao-principal">
       {{ texto }}
    </button>
</template>

<style scoped>

.botao-principal{
    border-radius: 2rem;
    background-color: var(--coral);
    padding: 0.5rem 1rem;
    font-weight: 700;
    color: var(--creme, #FFFAF3);
    box-shadow: 4px 4px 15px 0px rgba(255, 115, 76, 0.25);
    cursor: pointer;
   transition: 0.2s;

   display: flex;
  justify-content: center;
  align-items: center;
}

.botao-principal:hover {
  background: var(--ocre-hover, #D1451E);
}
</style>