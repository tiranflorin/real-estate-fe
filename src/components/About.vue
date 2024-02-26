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
    <template #heading>Ecosystem</template>
    ElasticSearch, Chat-GPT
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Sources</template>
    Data aggregated from:
    <br />
    <a href="#" target="_blank" rel="noopener">Facebook Groups</a>
    <br />
    <a href="#" target="_blank" rel="noopener">OLX</a>
    <br />
    <a href="#" target="_blank" rel="noopener">Independent listings</a>
    <br />
    More details are available on each listing.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support us</template>
    As an independent project, the Real Estate Finder relies on community backing for its sustainability. You can help
    us by
    <a href="/" rel="noopener">becoming a sponsor</a>
  </WelcomeItem>
</template>
