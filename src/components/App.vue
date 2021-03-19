<template>
  <div>
    <h1>自動販売機</h1>
    
    <div>
      <button v-on:click="onSelect()">Add 1</button>
      <p>Clicked {{ counter }} times.</p>
    </div>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      counter: 0
    }
  },
  methods: {
    onSelect:function() {
      this.counter++;
    }
  }
};
</script>