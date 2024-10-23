<template>
  <div class="list-wrap">
    <ul>
      <li>
        <span class="checkbox-wrap">
          <input
            type="checkbox"
            name=""
            class="checkbox-input"
            id="checkList00"
          />
        </span>
        <span class="inputTxt-wrap">
          <input type="text" name="" id="" placeholder="간지나게 숨쉬기" />
        </span>
      </li>
    </ul>
    <div class="add-btn-wrap">
      <button type="button" class="add-list" @click="add - list">+</button>
    </div>
  </div>
</template>

<script setup>
function add() {
  alert('...');
}
</script>

<style lang="scss" scoped>
.list-wrap {
  padding: 1.6rem 1rem;
}

.add-btn-wrap {
  margin: 1.6rem 0 0 0;
  text-align: right;
}

.add-list {
  display: block;
  width: 100%;
  padding: 0.5rem 1rem;
  background: #ffffff;
  border: none;
  border-radius: 1rem;
  font-size: 2rem;
}

ul {
  display: flex;
  flex-direction: column;
  gap: 1rem;

  li {
    display: flex;
  }
}

.checkbox-wrap {
  display: block;
}

.checkbox-wrap input {
  display: block;
  width: 2rem;
  height: 2rem;
  border-color: #ccc;
  outline-color: #ccc;
}

.inputTxt-wrap {
  width: calc(100% - 2rem);
}

.inputTxt-wrap input {
  display: block;
  width: 100%;
  padding: 0 0 0 1rem;
  line-height: 2rem;
  font-size: 1.6rem;
}

.inputTxt-wrap input:focus {
  border: none;
  outline: none;
}

.inputTxt-wrap input::placeholder {
  color: #ccc;
}
</style>
