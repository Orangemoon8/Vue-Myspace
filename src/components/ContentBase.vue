<template>
  <div class="home">
    <div class="container">
      <div class="card">
        <div class="card-body">
          <slot></slot>
        </div>
      </div>
    </div>
  </div>
</template>
 

<sciprt>
    export default {
        name:"ContentBase",
    }
</sciprt>

<style scoped>
.container {
  margin-top: 20px;
}
</style>