<script setup>
import GoalDirection from './components/GoalDirection.vue'
import Growth from './components/Growth.vue'
import Resilience from './components/Resilience.vue'
import SelfBelief from './components/SelfBelief.vue'
import Visioning from './components/Visioning.vue'
</script>

<template>
  <div>
    <GoalDirection>
      <template slot="header">
        <h2>Box Header</h2>
      </template>
      <template slot="body">
        <p>This is the box body.</p>
      </template>
      <template slot="footer">
        <p>This is the box footer.</p>
      </template>
    </GoalDirection>
  </div>
</template>

<script>
import BoxComponent from './BoxComponent.vue'

export default {
  components: { BoxComponent }
}
</script>
