<template>
  <div class="dashboard-container">
    <el-button type="primary" @click='goto_console' round>Go to AWS Console</el-button>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  methods: {
    goto_console() {
      this.$message({
        type: 'success',
        message: "calling func goto_console",
        });
    },
  }
}

</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
    text-align: center;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
