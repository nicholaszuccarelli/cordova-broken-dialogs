<template>
  <q-page class="flex flex-center">
    <q-btn label="Open Dialog" @click="dialogOpen = true" />

    <q-dialog v-model="dialogOpen">
      <q-card>
        <q-card-section>
          Double tap outside to close it on v1.22.1
        </q-card-section>
      </q-card>
    </q-dialog>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      dialogOpen: false
    }
  }
}
</script>
