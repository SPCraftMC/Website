<script setup lang="ts">
import PageHeader from '@/components/PageHeader.vue'
import FirstScreen from '@/components/FirstScreen.vue'
import PageFooter from '@/components/PageFooter.vue'

import DescriptionPage from '@/components/DescriptionPage.vue'
</script>

<template>
  <div>
    <header>
      <PageHeader></PageHeader>
    </header>

    <main>
      <FirstScreen></FirstScreen>
      <div style="position: relative;">
        <DescriptionPage></DescriptionPage>
      </div>
    </main>

    <footer>
      <PageFooter></PageFooter>
    </footer>
  </div>
</template>
