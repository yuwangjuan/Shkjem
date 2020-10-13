<template>

<div class="newsDetails-box"> 
  <div class="NewsDetails">
    <div class="left-box">
          <div class="bread-crumb">
            <breadcrumb></breadcrumb>
            <div class="gallery-box">
                <p class="gallery-tip">网站只列出部分课件，没找到也可以联系客服人工代寻，QQ 2445981459 微信 hungpeng8</p>
            </div>
          </div>
          <div class="content">
              <div class="content-detail">
                <p>企业数据化管理变革 数据治理与统筹方案_赵兴峰_北京_2016.08_250_PDF带书签目录_14171486</p>
                <img class="content-pic" src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
                <p class="book-info-title">电子书说明：</p>
                <p class="book-info-detail">1.关于本书的内容介绍、目录、详情等请在京东、淘宝、当当之类的售书网站查看，由于工作量巨大，本站不再全部展示，仅展示封面作参考。请务必核对标题、版本(标题含有作者.页数.出版时间等信息)和封面,确定封面是否和你在售书网站上所见一样，一般看 封面正确，那就错不了.本站主要是提供此书的电子书下载.</p>
                <p class="book-info-detail">2.非特殊说明，本站所有pdf均为高清扫描。若是文字版，标题有“文字版”说明。(文字版是文字可以复制，图片和文字都有，并非只有文字)</p>
                <p class="book-info-detail">3.所有电子书均为完整版，人工审核，若缺页包退、包换。每本100%带文字书签目录（词典/小说/繁体书/不带），点击可跳转到指定章节，非网上那种差质量PDF能比,放心购买.</p>
                <p class="book-info-detail">4.更多信息请查看点此查看</p>
              </div>
          </div> 
          <div class="content-guess">
            <p class="guess-title">猜你喜欢</p>
             <div class="img-item" >
              <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
              <p class="title">前端开发入门到实践</p>
              <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
            </div>
            <div class="img-item" >
              <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
              <p class="title">前端开发入门到实践</p>
              <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
            </div>
            <div class="img-item" >
              <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
              <p class="title">前端开发入门到实践</p>
              <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
            </div>
            <div class="img-item" >
              <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
              <p class="title">前端开发入门到实践</p>
              <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
            </div>
            <div class="img-item" >
              <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
              <p class="title">前端开发入门到实践</p>
              <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
            </div>
            <div class="img-item" >
              <img src="https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg" alt="">
              <p class="title">前端开发入门到实践</p>
              <p class="money"><span>￥29.9</span><span class="sale-num">销量：7</span></p>
            </div>
          </div>
      </div>
      <div class="right-box">
        <div class="right-box-content">
          <p class="money"><span class="point">10</span>&nbsp;积分</p>
          <p class="vip">VIP 可8折观看</p>
          <p class="login" @click="goToLogin">请先登录</p>
          <p class="tips">下载地址为百度网盘，若地址失效或有误，请联系QQ:2445981459, 或微信hungpeng8</p>
        </div>
        <div class="right-box-content-new">
          <p class="news-tilte">最新视频</p>
          <div class="each-item">
            <div class="each-left">
              <img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" alt="">
            </div>
            <div class="each-right">
              <p>好吃的汉堡,好吃的汉堡，好像hi的哈哈哈哈哈哈</p>
              <p class="each-right-money">￥10元</p>
            </div>
          </div>
          <div class="each-item">
            <div class="each-left">
              <img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" alt="">
            </div>
            <div class="each-right">
              <p>好吃的汉堡,好吃的汉堡，好像hi的哈哈哈哈哈哈</p>
              <p class="each-right-money">￥10元</p>
            </div>
          </div>
          <div class="each-item">
            <div class="each-left">
              <img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" alt="">
            </div>
            <div class="each-right">
              <p>好吃的汉堡,好吃的汉堡，好像hi的哈哈哈哈哈哈</p>
              <p class="each-right-money">￥10元</p>
            </div>
          </div>
          <!-- <el-divider style="height:0.5px;"/> -->
          <!-- <e l-row>
            <el-col :span="8" v-for="(o, index) in 2" :key="o" :offset="index > 0 ? 2 : 0">
              <el-card :body-style="{ padding: '0px' }">
                <img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" class="image">
                <div style="padding: 14px;">
                  <span>好吃的汉堡</span>
                  <div class="bottom clearfix">
                    <time class="time">{{ currentDate }}</time>
                    <el-button type="text" class="button">操作按钮</el-button>
                  </div>
                </div>
              </el-card>
            </el-col>
          </el-row> -->
        </div>
      </div>
  </div>
</div> 
</template>

<script>
import breadcrumb from '../components/crumb'
export default {
  name: "NewsDetails",
  components: {
    breadcrumb
  },
  data() {
    return {
      levelList:[],
    };
  },
  
  created() {
   
  },
  mounted() {
 
  },
  methods: {
      goToLogin(){
        this.$router.push('/login')
      }
  }
};
</script>

<style lang="scss" scoped>
.newsDetails-box{
  width:100%;
  background:#f1f2f3;
 
    .NewsDetails {
      width: 80%;
      height: 100%;
      margin:0 auto;
      padding-bottom:50px;
    //overflow: hidden;
  // background-color: #f1f2f3;
    .left-box{
      width:70%;
      display:inline-block;
      // border:1px solid #afa;
        .bread-crumb{
          width:100%;
          // margin:0 auto;
          height:80px;
          padding-top:20px;
          .gallery-box{
            margin-top:20px;
            margin-bottom:10px;
            .gallery-tip{
              color:red;
              text-align:center;
            }
          }
        }
      .content{
        width:100%;
        height:100%;
        background:#fff;
        margin-bottom:30px;
        // margin:0 auto;
          .content-detail{
           padding:20px;
           .content-pic{
             width:30%;
             height:100%;
             margin:0 auto;
             text-align:center;
             margin-left:35%;
             margin-top:20px; 
           }
           .book-info-title{
             font-weight:600;
           }
           .book-info-detail{
             font-size:14px;
             line-height:24px;
           }
          }
      }
      .content-guess{
        width:100%;
        height:100%;
        background:#fff;
        padding-bottom:30px;
          .guess-title{
              padding:20px;
            }
            .img-item{
            width:30%;
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
    }
    .right-box{
    display:inline-block;
    width:29%;
    // border:1px solid red;
    vertical-align:top;
    margin-top:60px;
      .right-box-content{
        margin-left:30px;
        width:90%;
        height:200px;
        background:#fff;
        .money{
          text-align: center;
          font-size:18px;
          padding-top:20px;
          .point{
            font-size:26px;
            color:red;
          }
        }
        .vip{
          font-size:14px;
          color:#999;
          text-align: center;
          padding:7px 0;
        }
        .login{
          text-align: center;
          width:85%;
          height:40px;
          background:#21a3fe;
          margin:0 auto;
          color:#fff;
          line-height: 40px;
          margin-top:20px;
          cursor:pointer;
        }
        .tips{
          font-size:13px;
          color: orange;
          margin:5px 20px;
        }
      }
      .right-box-content-new{
        margin-top:20px;
        margin-left:30px;
        width:90%;
        // height:200px;
        background:#fff;
          .news-tilte{
            padding:20px 20px;
          }
          .each-item{
            width:90%;
            margin:0 auto;
            padding-bottom:20px;
            .each-left{
              width:50%;
              
              display:inline-block;
                img{
                    height:100px;
                    width:100%;
                }
            }
            .each-right{
              width:45%;
              display:inline-block;
              vertical-align:top;
              margin-left:10px;
                .each-right-money{
                    margin-top:10px;
                }
            }
          }
      }
    }
  }
  
} 
</style>