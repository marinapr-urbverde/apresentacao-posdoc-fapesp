<template>
  <footer v-if="!$frontmatter.semRodape" class="rodape">
    <span>Território, Mudanças Climáticas e Equidade · Pós-doutorado FAPESP · IAU-USP</span>
    <span>{{ $nav.currentPage }}</span>
  </footer>
</template>
