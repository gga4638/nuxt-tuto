<template>
  <div>
    <h2>this is Child vue</h2>
    <p> {{ $props.foobar }}</p>
    <BaseFooCustomButton />
  </div>
</template>

<script>
export default {
  props: [
    'foobar',
  ]
}
</script>
