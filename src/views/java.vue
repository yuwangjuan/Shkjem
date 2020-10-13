<template>
<div>
  <div class="home" >
      <!-- <div class="search-box"> -->
        <p class="title-item">Java</p>
      <!-- </div> -->
      
  </div>
  
  <div class="content-box">
    <div class="gallery-box">
        <p class="gallery-tip">网站只列出部分课件，没找到也可以联系客服人工代寻，QQ 2445981459 微信 hungpeng8</p>
      </div>
      <div class="img-item" @click="showDetailJava">
        <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
        <p class="title">前端开发入门到实践</p>
        <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
      </div>
      <div class="img-item">
        <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
        <p class="title">前端开发入门到实践</p>
        <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
      </div>
      <div class="img-item">
        <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
        <p class="title">前端开发入门到实践</p>
        <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
      </div>
      <div class="img-item">
        <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
        <p class="title">前端开发入门到实践</p>
        <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
      </div>
      <div class="img-item">
        <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
        <p class="title">前端开发入门到实践</p>
        <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
      </div>
      <div class="img-item">
        <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
        <p class="title">前端开发入门到实践</p>
        <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
      </div>
      <div class="img-item">
        <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
        <p class="title">前端开发入门到实践</p>
        <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
      </div>
  </div>
  <div class="">

  </div>
</div>
</template>
 
<script>

export default {
  name: "java",
  components: {
   
  },
  data() {
    return { 
      input2:'',    
        }
  },
  created() {},

  computed: {
  },
  mounted() {

  },
  methods:{
    showDetailJava(){
      this.$router.push('./newsdetails')
    }
  }
};
</script>
 
<style lang="scss" scoped>
  .home{
    width:100%;
    height:100px;
    background:#f1f2f3;
      .title-item{
        text-align:center;
        line-height:100px;
        font-weight:600;
        font-size:24px;
      }
      
  }
  .content-box{
    width:90%;
    margin:0 auto;
    margin-top:20px;
    margin-bottom:50px;
    .gallery-box{
        margin-top:20px;
        margin-bottom:10px;
        .gallery-tip{
          color:red;
          text-align:center;
        }
      }
    .img-item{
      width:23%;
      margin:10px;
      display:inline-block;
      border:1px solid #f1f2f3;
      img{
        width:90%;
        height:90%;
        margin-left:5%;
        margin-top:5%;
      }
      .title{
        text-align:center;
      }
      .money{
        margin-left:5%;
        color:red;
        margin-bottom:5%;
        .sale-num{
          float:right;
          margin-right:5%;
          color:#666;
        }
      }
    }
  }
</style>