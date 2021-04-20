<template>
<el-header></el-header>
  <el-row :gutter="10">
    <el-col :xs="8"
            :sm="6"
            :md="4"
            :lg="3"
            :xl="1">
      <div class="grid-content bg-purple">1</div>
    </el-col>
    <el-col :xs="4"
            :sm="6"
            :md="8"
            :lg="9"
            :xl="11">
      <div class="grid-content bg-purple-light"></div>
    </el-col>
    <el-col :xs="4"
            :sm="6"
            :md="8"
            :lg="9"
            :xl="11">
      <div class="grid-content bg-purple"></div>
    </el-col>
    <el-col :xs="8"
            :sm="6"
            :md="4"
            :lg="3"
            :xl="1">
      <div class="grid-content bg-purple-light"></div>
    </el-col>
  </el-row>
  <h1>{{ msg }}</h1>
  <button @click="count++">count is: {{ count }}</button>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  data() {
    return {
      count: 0,
    }
  },
}
</script>
