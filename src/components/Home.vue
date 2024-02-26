<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
      <template #icon>
        <EcosystemIcon />
      </template>
      <template #heading>Teren</template>
      1000 m2 Oradea, 60.000 EUR
  </WelcomeItem>

  <WelcomeItem>
      <template #icon>
        <EcosystemIcon />
      </template>
      <template #heading>Teren</template>
      750 m2 Nojorid, 24.000 EUR
  </WelcomeItem>

  <WelcomeItem>
      <template #icon>
        <EcosystemIcon />
      </template>
      <template #heading>Teren + casa</template>
      750 m2 Biharia, 55.000 EUR
  </WelcomeItem>
</template>
