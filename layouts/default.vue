<template>
  <div class="troika">
    <div class="container">
      <div class="page">
        <div class="row">
          <div class="column illustration">
            <div class="illustration-inner">
            </div>
          </div>
          <div class="column page-content">
            <nuxt/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Default',
}
</script>

<style lang="scss">
.page-content {
  padding: 50vw;
}
</style>
