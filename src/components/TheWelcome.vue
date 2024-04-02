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
    <template #heading>Introduction :</template>
    Perkenalkan nama saya Ikhsan Ansari, biasa dipanggil Ikhsan saat ini saya berkuliah di
    Universitas Islam Riau Semester 4.
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan :</template>

    <ul>
      SD :
      <li>SD Negeri 025 Sekeladi</li>
    </ul>
    <ul>
      SMP :
      <li>MTS Darut Taqwa</li>
    </ul>
    <ul>
      SMA :
      <li>SMK Pembangunan Bagan Batu</li>
    </ul>
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>

    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a>
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"></a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Alamat :</template>
    Jalan Aur Kuning Ujung, Pekanbaru, Riau
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>

    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontak :</template>

    <ul>
      WA :
      <li>082249493933</li>
    </ul>
    <ul>
      No.Handphone :
      <li>082233839393</li>
    </ul>
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>

    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"></a>.

    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a>
    the official
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Media Sosial :</template>

    Follow akun Media Sosial saya :
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">Facebook</a>
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">Instagram</a> and
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">Tik Tok</a>
  </WelcomeItem>
</template>
