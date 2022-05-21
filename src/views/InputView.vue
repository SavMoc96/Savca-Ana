<template>
  <div class="input">
    <h1>This is an input page</h1>
  </div>
  <div>
    <input class="x(5)"  v-model="message" placeholder="x" />
    <p>Введённое сообщение: {{ message }}</p>
    <input class="y(7)" v-model="message" placeholder="y" />
    <p>Введённое сообщение: {{ message }}</p>
  </div>
</template>
