<template>
  <div>
    <h1 class="content-title">
      <font-awesome-icon icon="book" class="icon" /> About
    </h1>
    <div>
      <div class="about">
        <font size="4" face="ＭＳ Ｐゴシック,ＭＳ ゴシック"
          >筑波大学 修士1年 hogehoge
          <hr />
          筑波大学のhogehogeです。頑張ることが取り柄です。頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る頑張る。
        </font>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  components: {},
};
</script>

<style scoped>
.about {
  display: inline-flex;
  padding-left: 5%;
  padding-right: 5%;
}

.resent {
  margin-top: 50px;
}
.text {
  font-weight: 300;
}

@media screen and (max-width: 768px) {
  .about {
    flex-direction: column;
  }
  .me {
    margin: 0 auto;
  }
}
</style>