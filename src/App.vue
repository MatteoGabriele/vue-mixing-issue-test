<template>
  <div id="app">
    <p>{{ $foo }}</p>
    <p>{{ $$foo }}</p>
    <p>{{ $_foo }}</p>
    <p>{{ _foo }}</p>
    <p>{{ foo }}</p>
  </div>
</template>

<script>
import mixin from './mixin'

export default {
  name: 'app',
  mixins: [mixin]
}
</script>