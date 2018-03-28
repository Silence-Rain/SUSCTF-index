<template>
  <div class="parent-container container-fluid">
    <div class="header">
      <img src="http://static.myseu.cn/b2adde3bb55900474628196552748207" class="logo" />
      <div class="title">
        <div class="row">
          <p class="col-md-12">“华为杯”江苏省大学生</p>
        </div>
        <div class="row">
          <p class="col-md-12">网络空间安全精英邀请赛</p>
        </div>
        
        <div class="countdown row">
          <div class="countdown-item col-md-3">
            <p>{{days}}</p>
            <div>Days</div>
          </div>
          <div class="countdown-item col-md-3">
            <p>{{hours}}</p>
            <div>Hours</div>
          </div>
          <div class="countdown-item col-md-3">
            <p>{{mins}}</p>
            <div>Minutes</div>
          </div>
          <div class="countdown-item col-md-3">
            <p>{{secs}}</p>
            <div>Seconds</div>
          </div>
        </div>

      </div>
    </div>

    <div>
      <div class="content">

        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag.png"/>
            <p><span>00</span>平台地址</p>
          </div>
          <p>
            <a href="http://sus.xctf.org.cn/d60f9f98-fb1b-4d9b-9020-99e697760bf4/login/">“华为杯”江苏省大学生网络空间安全精英邀请赛</a>
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag.png"/>
            <p><span>01</span>简介</p>
          </div>
          <p>
            本次比赛由东南大学网络空间安全学院指导，东南大学网络安全联盟主办，赛宁网安提供网络安全攻防实战平台的技术支持。
          </p>
          <p>比赛面向全江苏省的高校，希望江苏各高校的新一届队员来到东南大学切磋技术，共同进步。
          </p>
          <p>本次比赛同时也作为为东南大学网络安全联盟CTF战队招新赛,面向全校招募新一届的队员，也借此机会选拔出真正对网安感兴趣的优秀后备人才。
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag.png"/>
            <p><span>02</span>比赛时间</p>
          </div>
          <p>
            北京时间2018年3月31日9:00~17:00，共8小时
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle">
            <img src="../assets/tag.png"/>
            <p><span>03</span>报名方式</p>
          </div>
          <p>
            截止3月28日24时
          </p>
          
          <p>
            <ul>
              <li>校内同学直接加入QQ群SUSCTF：429678492</li>
              <li>校外同学由主办方统一邀请</li>
              <li>各队信息按群文件模板统一发送至管理员处，等待管理员确认后为各队发放认证token</li>
            </ul>
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle">
            <img src="../assets/tag.png"/>
            <p><span>04</span>赛前宣讲</p>
          </div>
          <p>
            <ul>
              <li style="color:#FFD700;">时间：3月28日晚21:00</li>
              <li>地点：教二-103</li>
            </ul>
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle">
            <img src="../assets/tag.png"/>
            <p><span>05</span>参赛对象</p>
          </div>
          <p>每队三人</p>
          <p>
            <ul>
              <li>东南大学在校学生</li>
              <li>由主办方邀请的各个高校战队</li>
            </ul>
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle">
            <img src="../assets/tag.png"/>
            <p><span>06</span>比赛地点</p>
          </div>
          <p>东南大学九龙湖校区计算机楼2楼机房</p>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag.png"/>
            <p><span>07</span>题目</p>     
          </div>
          <p>
            传统的<a href="https://ctf-wiki.github.io/ctf-wiki/">CTF(Capture the flag)</a>模式。每道赛题均内置1个flag，大多数情况下为SUSCTF{example_flag}。提交包含SUSCTF{}的完整flag来获得相应分值。特殊情况会在题目中标明。 
          </p>
          <p>包含如下题目类型：</p>
          <ul>
            <li>Web 漏洞挖掘和利用</li>
            <li>Pwn 漏洞挖掘利用</li>
            <li>Crypto 密码分析</li>
            <li>Re 二进制程序逆向分析</li>
            <li>Misc 电子取证，流量分析，信息隐藏...</li>
          </ul>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag.png"/>
            <p><span>08</span>规则</p>
          </div>
          <p>
            <ul>
              <li>参赛队伍如有任何违规行为，将被取消比赛资格</li>
              <li>禁止不同参赛队伍合作，或者共享flag、hint等任何比赛相关信息</li>
              <li>禁止攻击比赛平台，如果发现平台漏洞，请务必向我们报告</li>
              <li>禁止在比赛中妨碍其他队伍解题，例如当你解完一道题后对环境进行破坏</li>
              <li>禁止往比赛平台发送大量流量，没有任何题目需要使用扫描器</li>
              <li>禁止对提交的flag进行爆破</li>
              <li>获奖的队伍必须提交完整结题报告</li>
              <li>大赛主办方有权修改包括赛题、规则等一切事项</li>
            </ul>
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag.png"/>
            <p><span>09</span>奖品</p>
          </div>
          <p>总排名：</p>
          <p>
            <ul>
              <li>一等奖（1名）</li>
              <li>二等奖（2名）</li>
              <li>三等奖（3名）</li>
            </ul>
          </p>
          <p>校内排名：</p>
          <p>
            <ul>
              <li>一等奖（1名）：机械键盘*3 + 荣誉证书</li>
              <li>二等奖（2名）：树莓派 + 荣誉证书</li>
              <li>三等奖（3名）：300元书籍 + 荣誉证书</li>
            </ul>
          </p>
        </div>

      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      curTime: 1520200000000,
      endTime: 1522458000000
    }
  }, 

  computed: {
    diff () {
      return (this.endTime - this.curTime) / 1000
    },

    days () {
      return Math.floor(this.diff / 86400)
    },

    hours () {
      return Math.floor((this.diff - this.days * 86400) / 3600)
    },

    mins () {
      return Math.floor((this.diff - this.days * 86400 - this.hours * 3600) / 60)
    }, 

    secs () {
      return Math.floor(this.diff - this.days * 86400 - this.hours * 3600 - this.mins * 60)
    }
  }, 

  mounted () {
    this.curTime = new Date().getTime()

    setInterval(() => {
      this.curTime += 1000
    }, 1000)
  }
}
</script>

<style scoped>

a {
  color: #E34A17;
}

.parent-container {
  width: 100%;
  height: 100%;
  font-size: 20px;
  background-image: url("http://static.myseu.cn/60c11717c07b6caee18fb9ef76fdf19e");
  background-attachment: fixed;
  /*background-repeat: round;*/
  background-size: cover; 
}

.header {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.logo {
  width: 200px;
  height: 200px;
  margin: 30px 0;
}

.title {
  width: 80%;
  text-align: center;
  color: #FFF;
  font-size: 40px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.countdown {
  display: flex;
  flex-direction: row;
}

.countdown-item {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.countdown-item p {
  font-size: 40px;
  margin-bottom: -5px;
}

.countdown-item div {
  width: 150px;
  text-align: center;
  border: 5px solid #FFF;
  border-radius: 20px;
  font-size: 27px;
}

.content {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 50px 0;
  color: #FFF;
  
}

.content-item {
  width: 70%;
  margin: 20px 0;
}

.content-item p {
  margin: 20px 0;
}

.content-subtitle {
  height: 60px;
  display: flex;
  flex-direction: row;
}

.content-subtitle img{
  height: 50px;
  z-index: 1000;
}

.content-subtitle p{
  color: #FF8C00;
  font-size: 25px;
  margin: 7px 0 0 -70px;
  z-index: 9999;
}

.content-subtitle span {
  margin-right: 40px;
  color: #FFF;
}

</style>