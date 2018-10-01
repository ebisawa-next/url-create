<template>
    <input class="input" type="text" :placeholder="placeholder">
</template>

<script>
export default {
  name: 'input',
  data () {
    return {
        placeholder: 'ここにテキストを入れてください'
    }
  }
}
</script>

<style scoped lang="scss">
.input {
    appearance: none;
    font-size: 1.4rem;
    padding: 10px;
    background-color: #fff;
    border-radius: 4px;
    border: 0;
    box-shadow: 0 2px rgba(0, 0, 0, .3) inset;
    &::-webkit-input-placeholder {
        color: #ebebeb;
    }
    &::-ms-input-placeholder {
        color: #ebebeb;
    }
    &::-moz-placeholder {
        color: #ebebeb;
    }
}
</style>
