<template>
  <div>
    <button @click="change">
      <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="long-arrow-alt-left" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="svg-inline--fa fa-long-arrow-alt-left fa-w-14 fa-7x"><path fill="currentColor" d="M134.059 296H436c6.627 0 12-5.373 12-12v-56c0-6.627-5.373-12-12-12H134.059v-46.059c0-21.382-25.851-32.09-40.971-16.971L7.029 239.029c-9.373 9.373-9.373 24.569 0 33.941l86.059 86.059c15.119 15.119 40.971 4.411 40.971-16.971V296z" class=""></path></svg>
    </button>
  </div>
</template>

<script>
export default {
  name: 'Back',
  methods: {
    change () {
      this.$parent.isGraph = false;
    }
  }
}
</script>

<style scoped>
  div {
    text-align: center;
    width: 40vw;
    height: 20vh;
  }
  button {
    width: 50%;
    text-align: center;
    vertical-align: center;
    border: none;
    background-color: transparent;
    margin-top: 20px;
  }
  svg {
    color: #fff;
  }
</style>
