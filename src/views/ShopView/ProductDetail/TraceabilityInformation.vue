<template>
  <div class="TraceabilityInformationBox">
    <span class="Title"> 溯源详情信息 </span>

    <div class="TraceTable">
      <el-descriptions direction="vertical" :column="4" border>
        <!-- 苹果基本信息 -->
        <el-descriptions-item label="苹果品种">红富士</el-descriptions-item>
        <el-descriptions-item label="产地">山东烟台</el-descriptions-item>
        <el-descriptions-item label="采摘日期">2025年05月15日</el-descriptions-item>
        <el-descriptions-item label="保质期">常温下7天，冷藏15天</el-descriptions-item>

        <!-- 农场信息 -->
        <el-descriptions-item label="果园名称">阳光果园</el-descriptions-item>
        <el-descriptions-item label="果园地址">山东省烟台市福山区果园路123号</el-descriptions-item>
        <el-descriptions-item label="种植面积">500亩</el-descriptions-item>
        <el-descriptions-item label="种植方式">绿色种植，无农药残留</el-descriptions-item>

        <!-- 质量检测信息 -->
        <el-descriptions-item label="检测机构">国家农产品质量检测中心</el-descriptions-item>
        <el-descriptions-item label="检测日期">2025年05月16日</el-descriptions-item>
        <el-descriptions-item label="检测结果">
          <el-tag type="success" size="small">合格</el-tag>
        </el-descriptions-item>
        <el-descriptions-item label="检测报告编号">SN20250516-AB1234</el-descriptions-item>

        <!-- 销售信息 -->
        <el-descriptions-item label="销售平台">阳光果园电商平台</el-descriptions-item>
        <el-descriptions-item label="发货日期">2025年05月17日</el-descriptions-item>
        <el-descriptions-item label="发货地址">山东省烟台市福山区果园路123号</el-descriptions-item>
        <el-descriptions-item label="物流信息">
          已发货，物流单号：1234567890
        </el-descriptions-item>
      </el-descriptions>
    </div>
  </div>
</template>

<script setup></script>

<style scoped lang="scss">
.TraceabilityInformationBox {
  width: 100%;
  height: auto;
  padding: 20px;
  display: flex;
  flex-direction: column;
}

.Title {
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 1px;
}

.TraceTable {
  width: 100%;
  height: auto;
  margin: 20px 0;
}
</style>
