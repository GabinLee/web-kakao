<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'NotoSans Regular','Malgun Gothic' }
html, body{ font-size: 10px; }
body{ background-color: #fff; word-wrap: break-word; word-break: keep-all; min-width: 1280px;}
a{ text-decoration: none; color: inherit; display: block; }
ul{ list-style: none; }
button{ background-color: transparent; border: none; }
button:hover{ cursor: pointer; }
button:focus{ outline: none; }

.mw1440{ min-width: 1280px; max-width: 1440px; margin: 0 auto; padding: 0 8rem; }
.fs16{ font-size: 16px; }
.fs14{ font-size: 14px; }
.fs12{ font-size: 12px; }
</style>
