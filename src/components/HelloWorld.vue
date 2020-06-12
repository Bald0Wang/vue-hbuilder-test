<template>
  <div class="hello">
    <Row>

        <i-col span="8"></i-col>
        <i-col span="8">
          <div class="center-right">
             <Poptip title="宁夏大学云计算与智能媒体信息处理实验室制作" content="iview组件支持" placement="right">
                <i-button>查看信息</i-button>
            </Poptip><br><br>
          </div>
        </i-col>
        <i-col span="8"></i-col>
    </Row>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.center-right{
    float: right;
}
</style>
