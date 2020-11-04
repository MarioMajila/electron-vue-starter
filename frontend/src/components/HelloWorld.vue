<template>
  <el-row>
    <el-col :span="24" >
      <div class="grid-content bg-purple-dark">MY PROJECT STARTER</div>
    </el-col>
  </el-row>
</template>

<script>
export default {
  data() {
    return {
      isCollapse: false,
      drawer: false,
    }
  },
  methods: {

  }
}
</script>

<style>
.el-row {
  margin-bottom: 20px;
}
.el-col {
  border-radius: 4px;
}
.bg-purple-dark {
  background: #99a9bf;
  padding: 20px;
  font-weight: bold;
  color: #d3dce6;
  text-align: center;
}
.bg-purple {
  background: #d3dce6;
}
</style>
