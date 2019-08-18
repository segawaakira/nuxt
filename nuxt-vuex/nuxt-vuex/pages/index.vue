<template>
  <div class="container">
    <div>
      <p>{{ $store.state.message }}</p>
      <!-- <button v-on:click="$store.commit('updateMessage')"> -->
      <button v-on:click="$store.commit('updateMessage','commit with payload')">
        update
      </button>
    </div>
  </div>
</template>

<script>
export default {
}
</script>
