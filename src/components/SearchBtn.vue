<template>
    <button class="search-button" @mouseover="hover = true" @mouseleave="hover = false">
      検索
    </button>
</template>

<script>
export default {
  data() {
    return {
      hover: false,
    };
  },
};
</script>

<style scoped>
.search-button {
  width: 200px;
  height: 100px;
  font-size: 48px;
  font-weight: bold;
  color: #0077a9;
  background-color: #cceeff;
  border: none;
  border-radius: 20px;
  transition: background-color 0.3s, color 0.3s;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.search-button:hover {
  background-color: #ffeb66; /* ホバー時の黄色 */
  color: #0077a9; /* テキストの色 */
}
</style>