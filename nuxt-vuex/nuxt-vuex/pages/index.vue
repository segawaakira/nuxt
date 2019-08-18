<template>
  <div class="container">
    <div>
      <p>{{ $store.state.message }}</p>
      <!-- <button v-on:click="$store.commit('updateMessage')"> -->
      <!-- <button v-on:click="$store.commit('updateMessage','commit with payload')"> -->
      <!-- <button v-on:click="$store.dispatch('updateMessageAction')"> -->
      <button v-on:click="$store.dispatch('updateMessageAction','Dispatch with payload')">
        update
      </button>
    </div>
  </div>
</template>

<script>
export default {
}
</script>
