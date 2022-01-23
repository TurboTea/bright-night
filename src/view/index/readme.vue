<template>
  <div class="readme-container">
        <code>
            <h2 class="title">系统说明：</h2>
            <ul class="detail">
              <li>
                  1.&nbsp;&nbsp;登录，注册，库房管理（入库单， 出库单，库存分配 库存余额表），产品管理（产品库存， 产品成本， 产品属性管理，产品列表），订单管理（订单报表， 所有订单， 所属员工， 订单发货， 生成发货订单），财务管理（记录出款和入款， 计算一段时间的利润），客户管理（客户基本信息， 客户销售， 客户订单管理， 客户关系管理）， 员工管理（员工基本信息， 员工权限， 入职新员工， 员工销售额管理）</li>
            </ul>
        </code>
  </div>
</template>
<script>
export default {

  data () {
    return {

    }
  }
}
</script>
<style type="text/css">
  li {
    list-style: none;
  }
  .readme-container {
    margin-top: 80px;
    margin-left: 50px;
    width: 90%;
    overflow: hidden;
    background: #eef1f6;
    padding: 20px;
  }
  .readme-container .title {
    padding-bottom: 20px;
  }
  .readme-container .detail>li {
    font-family: 微软雅黑;
    font-size: 15px;
    line-height: 3;
  }
</style>
