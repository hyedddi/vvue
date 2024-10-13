<template>
  <p><button type="button">+</button></p>
  <ul>
    <li>
      <span class="checkbox-wrap">
        <input
          type="checkbox"
          name=""
          class="checkbox-input"
          id="checkList00"
        />
        <label for="checkList00" class="checkbox-label">ㅇㅇㅇㅇㅇㅇ</label>
      </span>
    </li>
  </ul>
</template>

<script setup></script>

<style lang="scss" scoped>
@import '../assets/_variables.scss';
@import '../assets/_mixin.scss';
ul {
  @include flex-row(10px);
  li {
  }
}

.checkbox-wrap {
  display: $display-ib;
}
.checkbox-input {
  display: none;
}

.checkbox-label {
  display: block;
  padding: 0 0 0 2.5rem;
  line-height: 20px;
  font-size: 1.8rem;
}
</style>
