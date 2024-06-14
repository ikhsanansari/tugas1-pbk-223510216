<script setup>
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
      <DocumentationIcon />
    </template>
    <template #heading>Introduction</template>
    saya alumni dari SMK Negeri 2 Lubuk Basung dan Jurusan saya di SMK adalah Teknik Komputer
    Jaringan
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Alamat</template>
    Sekarang saya tinggal Di Pekanbaru jalan aur kuning ujung
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>
    Hobi saya adalah Bermain tenis meja
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Media Sosial</template>
    Instagram :ikhsanansaris
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>

    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"></a>
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
