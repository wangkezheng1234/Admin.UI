<template>
  <section style="padding:20px 20px 0px 0px;">
    <el-timeline>
      <el-timeline-item timestamp="版本 1.0.1" placement="top">
        <el-card>
          <h4>新增 日志管理-登录日志和操作日志</h4>
          <h4>优化 数据同步使用事物，数据同步SqlServer自增长处理。更新NuGet包到最新版本。</h4>
          <p>小雪转中雪 提交于 2020-3-28</p>
        </el-card>
      </el-timeline-item>
      <el-timeline-item timestamp="版本 1.0.0" placement="top">
        <el-card>
          <h4>新增 更新日志</h4>
          <h4>新增 缓存管理，手动清除缓存</h4>
          <h4>修复 接口管理-同步Api异常问题</h4>
          <p>小雪转中雪 提交于 2020-3-24</p>
        </el-card>
      </el-timeline-item>
    </el-timeline>
  </section>
</template>

<script>
export default {
  name: 'Welcome',
  data() {
    return {

    }
  }
}
</script>

<style scoped>
h2,h3,h4,h5 {
    font-weight: 400;
    color: #1f2f3d;
}
p {
    font-size: 14px;
    color: #5e6d82;
    line-height: 1.5em;
}
.el-timeline{
  padding-left: 15px;
}
</style>
