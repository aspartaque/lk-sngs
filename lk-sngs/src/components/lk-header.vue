<template lang="pug">
header
  .lk-container
    .lk-header.--display-flex
      .lk-header__logo
        a(href="#")
          include ../assets/svg/sngs-logo.svg
      .lk-header__nav.--display-flex
        .lk-header__contact.--display-flex
          a(href="#").--display-flex
            | +7 (999) 999 - 99 - 99
            include ../assets/svg/sngs-contact.svg
        .lk-header__exit.--display-flex
          a(href="#").--display-flex
            | Завершить сеанс
            include ../assets/svg/sngs-exit.svg
</template>

<style lang="scss">
@import '@/assets/scss/variables.scss';

header {
  width: 100%;
  height: 60px;
  border-bottom: 1px solid $border-color;
}

.lk-header {
  justify-content: space-between;
  align-items: center;
  height: 100%;
}

.lk-header__logo {
  
}

.lk-header__nav {
  height: 100%;
  align-items: center;
  a {
    color: $header-color;
    align-items: center;
  }
  svg {
    margin-left: 10px;
  }
}

.lk-header__contact {
  height: 100%;
  align-items: center;
  padding: 0 22px;
  border-left: 1px solid $border-color;
}

.lk-header__exit {
  height: 100%;
  align-items: center;
  padding: 0 22px;
  border-left: 1px solid $border-color;
}
</style>