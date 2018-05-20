<template>
<nav class="panel column is-offset-2 is-8">
  <p class="panel-heading">
    Vuejs Phonebook

    <button class="button is-link is-outlined">
      Add New
    </button>
  </p>
  <div class="panel-block">
    <p class="control has-icons-left">
      <input class="input is-small" type="text" placeholder="search">
      <span class="icon is-small is-left">
        <i class="fas fa-search" aria-hidden="true"></i>
      </span>
    </p>
  </div>
  <a class="panel-block">
    <span class="column is-6">
      marksheet
    </span>
    <span class="has-text-danger column is-2">삭제</span>
    <span class="has-text-info column is-2">수정</span>
    <span class="has-text-primary column is-2">보기</span>
  </a>
</nav>
</template>
