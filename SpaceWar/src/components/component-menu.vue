<template>
  <div>
    <div id="div_menu">
      <ButtonGroup size="large" vertical>
        <Button class="button_menu" id="button_home" size="large" type="default" icon="md-home" ghost></Button>
        <Button class="button_menu" id="button_help" size="large" type="default" icon="md-help" ghost></Button>
        <Button class="button_menu" id="button_restart" size="large" type="default" icon="md-refresh" ghost></Button>
      </ButtonGroup>
    </div>
  </div>
</template>

<script>
export default {
  name: 'component-menu'
}
</script>

<style scoped>
#div_menu {
  width: auto;
  height: auto;
  display: block;
  position: absolute;
  top: 15px;
  right: 15px;
  align-items: center;
  z-index: 1;
}

.button_menu{
  color:#f8f8f9;
}
</style>
