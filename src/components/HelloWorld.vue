<template>
  <div class="hello">
    <input type="text" :value="msg" @input="$emit('update:msg', $event.target.value)">
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>