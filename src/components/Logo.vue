<template>
  <g-link to="/" class="logo" title="Back to home">
    <transition name="theme">
      <div v-if="color == 'dark'" style="display: flex;">
        <g-image src="~/assets/img/iDesignzone.svg" alt="logo" />
        <h2 style="line-height: 0;margin-left:10px;">iDesignzone</h2>
        <div style="margin-left:30px;color: #fff;">
          <h2 style="line-height: 0;margin-bottom: 8px;font-size: 30px;margin-top: 12px;">iDesignzone</h2>
          <span style="margin-top: -15px;">Knowledge Base</span>
        </div>
      </div>
    </transition>
    <transition name="theme">
      <div v-if="color == 'bright'" style="display: flex;">
        <g-image src="~/assets/img/iDesignzone.svg" alt="logo" />
        <div style="margin-left:30px;">
          <h2 style="line-height: 0;margin-bottom: 8px;font-size: 30px;margin-top: 12px;">iDesignzone</h2>
          <span style="margin-top: -15px;">Knowledge Base</span>
        </div>
      </div>
    </transition>
  </g-link>
</template>

<script>
export default {
  props: {
    color: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
.logo {
  height: 40px;
  display: block;
  transition: color .15s ease-in-out;
  color: $textBright;
  position: relative;
  perspective: 200px;

  div {
    height: 40px;
    position: absolute;
    top: 0;
    left: 0;
  }

  img {
    height: 100%;
    width: auto;
  }
}

.theme-enter-active, .theme-leave-active {
  transition: opacity .15s ease-in-out;
}
.theme-enter, .theme-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>


