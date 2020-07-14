<template>
   <div class="editor">
    <Header>検索</Header>
    <textarea name="memo" v-model="memoBody"></textarea>
    <button @click="save">探す
    </button>
  </div>
</template>
