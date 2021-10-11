<template>
  <div>
    <div class="header-wrapper">
      <div class="header-title">
        <p>ヘッダー</p>
      </div>
      <div class="header-lists">
        <ul class="header-list">
          <li>新規登録</li>
          <li>ログイン</li>
          <li>マイページ</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
li {
  list-style: none;
}
.header-wrapper {
  display: flex;
  justify-content: space-around;
  border-bottom: .5px solid black;
}
.header-lists {
  vertical-align: bottom;
}
.header-list {
  display: flex;
}
.header-list > li {
    margin-left: 20px;
}
.header-list > li:first-child {
  margin-left: 0;
}
</style>
