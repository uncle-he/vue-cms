<template>
  <div class="cmt-container">
    <h3>发表评论</h3>

    <hr>

    <textarea placeholder="请输入要BB的内容(最多BB120字)" maxlength="120"></textarea>

    <mt-button type="primary" size="large">发表评论</mt-button>


    <div class="cmt-list">
      <div class="cmt-item">
        <div class="cmt-title">
          第1楼 &nbsp;&nbsp; 用户: 匿名用户 &nbsp;&nbsp; 发表时间: 2019-10-04 09:33:17
        </div>
        <div class="cmt-body">
          白日依山尽
        </div>
      </div>
      <div class="cmt-item">
        <div class="cmt-title">
          第2楼 &nbsp;&nbsp; 用户: 匿名用户 &nbsp;&nbsp; 发表时间: 2019-10-04 09:33:17
        </div>
        <div class="cmt-body">
          风吹草地见牛羊
        </div>
      </div>
      <div class="cmt-item">
        <div class="cmt-title">
          第3楼 &nbsp;&nbsp; 用户: 匿名用户 &nbsp;&nbsp; 发表时间: 2019-10-04 09:33:17
        </div>
        <div class="cmt-body">
          我信了！真的
        </div>
      </div>
      <div class="cmt-item">
        <div class="cmt-title">
          第4楼 &nbsp;&nbsp; 用户: 匿名用户 &nbsp;&nbsp; 发表时间: 2019-10-04 09:33:17
        </div>
        <div class="cmt-body">
          浪费时间
        </div>
      </div>

    </div>


    <mt-button type="danger" size="large" plain>加载更多</mt-button>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
  .cmt-container {
    h3 {
      font-size: 18px;
    }
    textarea {
      font-size: 14px;
      height: 85px;
      margin: 0;
    }

    .cmt-list {
      margin: 5px 0;
      .cmt-item {
        font-size: 13px;
        .cmt-title {
          line-height: 30px;
          background-color: #ccc;
        }
        .cmt-body {
          line-height: 35px;
          text-indent: 2em;
        }
      }
    }
  }
</style>