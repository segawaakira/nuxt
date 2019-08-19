<template>
  <div class="container">
    <div>

      <!-- ▼ クラシックモード -->
      <!-- <p>{{ $store.state.message }}</p> -->
      <!-- <button v-on:click="$store.commit('updateMessage')"> -->
      <!-- <button v-on:click="$store.commit('updateMessage','commit with payload')"> -->
      <!-- <button v-on:click="$store.dispatch('updateMessageAction')"> -->
      <!-- <button v-on:click="$store.dispatch('updateMessageAction','Dispatch with payload')">
        update
      </button> -->
      <!-- ▲ クラシックモード -->

      <!-- ▼ モジュールモード -->
      <p>{{ $store.state.hello.message }}</p>
      <!-- <button v-on:click="$store.commit('updateMessage')"> -->
      <!-- <button v-on:click="$store.commit('updateMessage','commit with payload')"> -->
      <!-- <button v-on:click="$store.dispatch('updateMessageAction')"> -->
      <button v-on:click="$store.dispatch('hello/updateMessageAction','Dispatch with payload')">
        update
      </button>
      <!-- ▲ モジュールモード -->
    </div>
  </div>
</template>

<script>
export default {
}
</script>
