<script setup lang="ts">
useHead({
  title: 'Nosotros | Jarkol Technologies',
  meta: [
    { name: 'description', content: 'Transformamos desafíos geotérmicos y geofísicos en oportunidades, guiándolo hacia el futuro de la exploración energética.' },
  ],
  link: [
    { rel: 'icon', type: 'image/png', href: '/jarkol/logo/jarkol.png' }
  ],
})
</script>

<template>
  <section class="lg:pt-20 lg:pb-20 md:pt-24 md:pb-24">
    <AtomsContainer>
      <SectionsHeroAbout />
      <SectionsHomeHeroInfo />
      <SectionsHomeHeroMisionAndVision />
      <SectionsHomeHeroCommunities />
    </AtomsContainer>
  </section>
</template>