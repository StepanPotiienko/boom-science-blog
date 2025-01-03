<script setup lang="ts"></script>

<template>
  <aside>
    <div id="header-menu">
      <div id="heading">
        <div id="header-menu-icon"></div>
        <div id="header-title">Boom — Science!</div>
        <div class="separator"></div>
      </div>
    </div>
  </aside>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap');

#header-menu {
  width: 30%;
  height: 100%;
  background-color: #232c39;
}

#header-title {
  font-size: 32px;
  font-weight: 800;
  font-style: italic;
}

.separator {
  width: 300px;
  height: 3px;
  background-color: #e0fbfc;
}
</style>
