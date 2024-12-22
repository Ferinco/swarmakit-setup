<script setup lang="ts">
import RightDiv from './RightDiv.vue'


</script>

<template>
  <div class="parent-div">
    <div class="child child-1">
      <div class="child-1-content">
        <h1>I'm a Samurai!</h1>
      </div>
    </div>
    <div class="child child-2">
      <RightDiv />
    </div>
  </div>
</template>

<style scoped>
.parent-div {
  display: flex;
  width: 100vw;
  height: 100vh;
}

.child {
  text-align: center;
  padding: 20px;
}

.child-1 {
  flex: 3;
  background-image: url('/2150169179.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  padding: 0;
  box-shadow: rgba(0, 0, 0, 0.15) 1.95px 1.95px 2.6px !important;
}

.child-2 {
  flex: 2;
  background-color: white;
}

.child-1-content {
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  justify-content: end;
  background: linear-gradient(to top right, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0));
  align-items: end;

}

h1 {
  display: flex;
  justify-content: end;
  padding: 5px 20px;
  font-size: 4.2em;
  line-height: 1.1;
}
@media (max-width: 864px) {
  .child-1 {
    display: none;
  }
}
</style>
