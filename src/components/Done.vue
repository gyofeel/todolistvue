<template>
  <section class="done">
    <h3>Done</h3>
    <div class="doneitems">
      <!-- 컴포넌트로! -->
      <div class="doneitem">
        <span>test</span>
        <div class="buttons">
          <button>다시 할일로</button>
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
.done {
  width: 40%;
  min-height: 50px;
  max-height: 250px;
  overflow-y: scroll;
  background-color: #6ab04c;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  border-radius: 10px;
  margin-top: 15px;
  padding: 10px 0;
}
.done .doneitems {
  display: flex;
  flex-flow: column nowrap;
  width: 70%;
}
.done .doneitem {
  padding: 5px 10px;
  background-color: #badc58;
  border-radius: 4px;
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  align-items: center;
}
</style>