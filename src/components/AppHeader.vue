<template functional>
  <header
    class="header"
    key="header"
  >
    <div class="header__logo">
      <img
        class="logo__image"
        src="@/assets/logo.png"
        alt="VPomodoro logo"
      />
      <h1 class="logo__title">V-Pomodoro</h1>
      
    </div>
  </header>
</template>

<style lang="stylus" scoped>
  .header
    alignCenter()

  .header__logo
    alignCenter()

  .logo__image
    width 3.8rem

  .logo__title
    font-size 2rem
    margin-left 1rem

</style>
