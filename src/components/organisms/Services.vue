<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim nobis dolorum quia harum repellendus nisi ad quasi? Ullam sunt hic iure harum porro ad, laboriosam veritatis natus quaerat sint eaque.
      Loren"
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim nobis dolorum quia harum repellendus nisi ad quasi? Ullam sunt hic iure harum porro ad, laboriosam veritatis natus quaerat sint eaque.
      Loren"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim nobis dolorum quia harum repellendus nisi ad quasi? Ullam sunt hic iure harum porro ad, laboriosam veritatis natus quaerat sint eaque.
      Loren"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
