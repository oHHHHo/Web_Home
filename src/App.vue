<template>
  <div id="app">
    <!-- Navbar  头 -->
    <nav class="navbar">
      <div class="inner-width">
        <a href="#" class="logo"></a>
        <div class="navbar-menu">
          <a href="#home">首页</a>
          <a href="#board">服务</a>
          <a href="#summary">简介</a>
          <a href="https://admin.wuxin5.top" target="_blank">后台管理系统</a>
          <a href="#home" title="邮箱 w@w.wuxin5.top" onclick="return alert('邮箱 w@w.wuxin5.top')">联系方式</a>
          <a >lw008991</a>
        </div>
      </div>
    </nav>

    <!-- Home -->
    <section id="home">
      <div class="inner-width">
        <div class="content">
          <h1>Hi I'm </h1>
          <div class="buttons">
            <a href="/index1.html">登陆</a>
            <a href="#" onclick="return alert('占未开放注册功能，请使用下方第三方登陆')">注册</a>
          </div>

          <!-- autoplay loop -->
          <video autoplay loop muted>
            <source src="./images/bg.mp4">
          </video>
        </div>
      </div>
    </section>

    <!-- Service -->
    <section id="board" class="dark">
      <div class="inner-width">
        <div>
          <h1 class="section-title">Services</h1>
          <div class="services">

            <div class="service">
              <i class="icon fas fa-paint-brush"></i>
              <h4>Design</h4>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <div class="service">
              <i class="icon fas fa-pager"></i>
              <h4>Build Websites</h4>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <div class="service">
              <i class="icon fas fa-database"></i>
              <h4>Manage Databases</h4>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <div class="service">
              <i class="icon fab fa-android"></i>
              <h4>Android Apps</h4>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <div class="service">
              <i class="icon fas fa-credit-card"></i>
              <h4>Ui Design</h4>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <div class="service">
              <i class="icon fas fa-keyboard"></i>
              <h4>Edit Texts</h4>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>

          </div>
        </div>
      </div>

    </section>

    <!-- About -->
    <section id="summary" class="dark1">
      <div class="inner-width">
        <h1 class="section-title">简介</h1>
        <div class="about-content">
          <img src="./images/triller.png" alt="" class="about-pic">
          <div class="about-text">
            <h3>
              <span>Developer</span>
              <span>Designer</span>
            </h3>
            <ul>
              <li>Weex+Vue+WebSocket ：使用Weex跨平台开发工具，整合集成VUE框架，完成移动端功能开发，并集成WebSocket实现即时消息（文章推荐、私信）的推送</li>
              <li>Vue+Echarts ： 自媒体系统使用Vue开发关键，集成Echarts图表框架，完成相关粉丝画像、数据分析等功能</li>
              <li>Vue+Echarts+WebSocket ： 管理系统也是使用Vue开发，集成Echarts，完成网站统计、内容统计等功能，集成WebSocket，实现系统看板实时数据自动化更新</li>
              <li>Spring-Cloud-Gateway : 微服务之前架设的网关服务，实现服务注册中的API请求路由，以及控制流速控制和熔断处理都是常用的架构手段，而这些功能Gateway天然支持</li>
              <li>Junit : 在持续集成思想中，单元测试偏向自动化过程，项目通过Junit+Maven的集成实现这种过程</li>
              <li>运用Spring Boot快速开发框架，构建项目工程；并结合Spring Cloud全家桶技术，实现后端个人中心、自媒体、管理中心等微服务。</li>
              <li>运用WebMagic爬虫技术，完善系统内容自动化采集 未发布</li>
              <li>运用Kafka完成内部系统消息通知；与客户端系统消息通知；以及实时数据计算</li>
              <li>运用MyCat数据库中间件计算，对系统数据进行分开分表，提升系统数据层性能</li>
              <li>运用Redis缓存技术，实现热数据的计算，NoSession等功能，提升系统性能指标</li>
              <li>运用Zoookeeper技术，完成大数据节点之后的协调与管理，提升系统存储层高可用</li>
              <li>使用Mysql存储用户数据，以保证上层数据查询的高性能</li>
              <li>使用Mongo存储用户热数据，以保证用户热数据高扩展和高性能指标</li>
              <li>使用FastDFS作为静态资源存储器，在其上实现热静态资源缓存、淘汰等功能</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>使用minio作为对象存储,存放静态资源，减小服务器带宽压力</li>
              <li>运用ES搜索技术，对冷数据、文章数据建立索引，以保证冷数据、文章查询性能</li>
              <li>运用Neo4j知识图谱技术，分析数据关系，产出知识结果，并应用到上层业务中，以帮助用户、自媒体、运营效果/能力提升。比如粉丝等级计算</li>
              <li>运用AI技术，来完成系统自动化功能，以提升效率及节省成本。比如实名认证自动化</li>
            </ul>
          </div>
        </div>

        <div class="skills">
          <div class="skill">
            <div class="skill-info">
              <span>HTML</span>
              <span>90%</span>
            </div>
            <div class="skill-bar html"></div>
          </div>

          <div class="skill">
            <div class="skill-info">
              <span>CSS</span>
              <span>80%</span>
            </div>
            <div class="skill-bar css"></div>
          </div>

          <div class="skill">
            <div class="skill-info">
              <span>Javascript</span>
              <span>70%</span>
            </div>
            <div class="skill-bar js"></div>
          </div>

          <div class="skill">
            <div class="skill-info">
              <span>java</span>
              <span>70%</span>
            </div>
            <div class="skill-bar java"></div>
          </div>

        </div>
      </div>
    </section>

    <!-- footer -->
    <div class="footer">
      &copy;2020-2021 性能组 &nbsp;&nbsp;版权所有
    </div>
  </div>
</template>

<script>
import './css/style.css'
export default {
  data() {
    return {
    };
  },
  methods: {
    clickmethond() {
      console.log("logout")
    }
  }
}
</script>

<style>
</style>
