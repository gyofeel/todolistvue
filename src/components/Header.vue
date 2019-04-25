<template>
  <section class="header">
    <h1 class="title">To Do List</h1>
    <input class="input" type="text" placeholder="할 일 입력 ...">
  </section>
</template>

<script>
export default {};
</script>

<style>
.header {
  width: 40%;
  height: 150px;
  background-color: #badc58;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  border-radius: 10px;
}
.header .title {
  text-decoration: underline;
}
.header .input {
  width: 70%;
  height: 30%;
  border-radius: 10px;
  border: none;
  padding: 5px 20px;
  font-size: 1.3rem;
  opacity: 0.5;
  transition: 0.7s;
}
.header .input:focus {
  outline: none;
  opacity: 1;
}
.header .input::placeholder {
  display: none;
  opacity: 0.5;
}
</style>