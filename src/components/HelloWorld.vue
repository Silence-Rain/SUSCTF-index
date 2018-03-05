<template>
  <div class="container">
    <div class="header">
      <img src="../assets/logo.png" class="logo" />
      <div class="title">
        <p>江苏省大学生网络空间安全精英邀请赛</p>
        <div class="countdown">
          <div class="countdown-item">
            <p>{{days}}</p>
            <div>Days</div>
          </div>
          <div class="countdown-item">
            <p>{{hours}}</p>
            <div>Hours</div>
          </div>
          <div class="countdown-item">
            <p>{{mins}}</p>
            <div>Minutes</div>
          </div>
          <div class="countdown-item">
            <p>{{secs}}</p>
            <div>Seconds</div>
          </div>
        </div>
      </div>
    </div>

    <div class="content">
      <div class="content-title">比赛介绍</div>
      <!-- <img src="../assets/divisor.png" class="divisor"/> -->

      <div class="content-detail">
        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag1.png"/>
            <p>简介</p>
          </div>
          <p>
            哈哈哈哈这是简介啊啊啊
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            
            <p>比赛时间</p>
            <img src="../assets/tag2.png"/>
          </div>
          <p>
            8小时 北京时间2018年3月31号9.00开始,3月31号17:00结束
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            
            <p>题目</p>
            <img src="../assets/tag3.png"/>
          </div>
          <p>
            传统的CTF(Capture the flag)模式。每道赛题均内置1个flag,大多数情况下为SUSCTF{example_flag},提交包含SUSCTF{}的完整flag来获得相应分值。特殊情况会在题目中标明。 
            包含如下题目类型：
            <ul>
              <li>Web 漏洞挖掘和利用</li>
              <li>Pwn 漏洞挖掘利用</li>
              <li>Crypto 密码分析</li>
              <li>Re 二进制程序逆向分析</li>
              <li>Misc 电子取证,流量分析,信息隐藏...</li>
            </ul>
          </p>
        </div>

        <div class="content-item">
          <div class="content-subtitle"> 
            <img src="../assets/tag4.png"/>
            <p>规则</p>
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
            <img src="../assets/tag5.png"/>
            <p>联系方式</p>
          </div>
          <p>
            哈哈哈哈这是联系方式啊啊啊
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
      days: 12,
      hours: 12,
      mins: 12,
      secs: 12
    }
  }
}
</script>

<style scoped>

.container {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  background: #222;
  font-size: 30px;
}

.header {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-image: url("../assets/cover.jpg");
  background-size: 100%;
}

.logo {
  width: 200px;
  height: 200px;
}

.title {
  color: #FFF;
  font-size: 55px;
}

.countdown {
  display: flex;
  flex-direction: row;
}

.countdown-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 0 20px;
}

.countdown-item div {
  width: 280px;
  text-align: center;
  border: 5px solid #FFF;
  border-radius: 20px;
}

.content {
  width: 100%;
  display: flex;
  flex-direction: column;
  padding: 50px;
  color: #FFF;
  background-image: url("../assets/content-bg.jpg");
  background-size: 100%;
}

.content-title {
  margin: 20px 0;
}

.divisor {
  height: 20px;
}

.content-detail {
  margin: 20px 0;
}

.content-item {
  margin: 20px 0;
}

.content-subtitle {
  display: flex;
  flex-direction: row;
  line-height: 60px;
}

.content-subtitle img{
  height: 60px;
}

</style>