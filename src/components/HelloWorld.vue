<template>
  <f7-app class="h">
    <f7-panel left cover theme-dark>
      <f7-navbar title="Left Panel" />
      <f7-block>Left panel content</f7-block>
    </f7-panel>

    <f7-panel right reveal>
      <f7-navbar title="Right Panel" />
      <f7-block>Right panel content</f7-block>
    </f7-panel>

    <f7-view main>
      <f7-page>
        <f7-navbar title="My App" />
        <f7-block>
          <f7-segmented>
            <f7-button panel-open="left">Left Panel</f7-button>
            <f7-button panel-open="right">Right Panel</f7-button>
          </f7-segmented>
        </f7-block>
      </f7-page>
    </f7-view>
  </f7-app>
</template>

<style lang="scss" scoped>
.h {
  height: 100vh;
}
</style>
