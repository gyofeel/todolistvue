<template>
  <section class="todo">
    <div class="items">
      <!-- 컴포넌트로! -->
      <div class="item">
        <div>
          <input type="checkbox">
          <span>vue로 todolist 만들기</span>
        </div>
        <div class="buttons">
          <button>삭제</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.todo {
  width: 40%;
  min-height: 100px;
  max-height: 250px;
  overflow-y: scroll;
  background-color: #badc58;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  border-radius: 10px;
}
.todo .items {
  width: 70%;
  height: 100%;
  padding: 10px 0;
}

.todo .item {
  font-size: 1rem;
  padding: 10px 10px;
  margin: 6px 0;
  border: 1px solid #130f40;
  border-radius: 4px;
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  align-items: center;
}
</style>