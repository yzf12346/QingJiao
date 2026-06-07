<section class="relative h-80">
  <img src="/banner.png" class="absolute h-full object-cover" />
  <div class="absolute z-20 w-full h-full">
    <div
      class="text-white absolute bottom-0 p-5 from-black to-transparent scheme-only-light bg-linear-to-t w-full"
    >
      <h2 class="text-5xl mb-2">青椒传媒</h2>
      <span class="text-xl text-zinc-100/50">
        让青椒开满全世界
      </span>
    </div>
  </div>
</section>

<article class="text-zinc-800">
  <section>
    <h3>我们是青椒传媒</h3>
    <p>
      一群不想只做“乙方工具人”的内容玩家。
      拍片、剪视频、搞直播、想创意——主业是把品牌变得有意思，副业是把无聊干掉。
    </p>
  </section>

  <section>
    <h3>我们可以做什么</h3>
    <h4>拍片子:</h4>
    <p>广告片、宣传片、短视频，能上电视也能刷抖音</p>
    <h4>做账号:</h4>
    <p>帮品牌养号、涨粉、做内容，不当“僵尸号”</p>
    <h4>搞直播:</h4>
    <p>从脚本到带货，帮你把流量变成销量</p>
    <h4>出点子:</h4>
    <p>活动策划、品牌包装，专治“没灵感”</p>
  </section>


  <section>
    <h3>我们的成就</h3>
    <div class="hscroll-container">
      <div class="item">
        <img src="/a_1.jpg" alt="" />
        <div>
          <h5>2015 珠峰大本营</h5>
          <p>为珠穆朗玛峰安装世界最高观光电梯，后因“影响日出氛围”被拆除。</p>
        </div>
      </div>
      <div class="item">
        <img src="/a_2.jpg" alt="" />
        <div>
          <h5>温暖冰岛计划</h5>
          <p>
            为了给寒冷的冰岛人民送去温暖，往活火山口倒了几吨助燃剂“免费地热供暖计划”。
          </p>
        </div>
      </div>
      <div class="item">
        <img src="/a_3.jpg" alt="" />
        <div>
          <h5>突破全宇宙包邮</h5>
          <p>完成人类首次太空直播带货，成交 0 单，点赞来自外星文明。</p>
        </div>
      </div>
      <div class="item">
        <img src="/a_4.jpg" alt="" />
        <div>
          <h5>投放广告到世界最低点</h5>
          <p>在 10909 米深处投放防水广告牌，目前仍在下沉。</p>
        </div>
      </div>
      <div class="item">
        <img src="/a_5.jpg" alt="" />
        <div>
          <h5>突破实现无人演讲</h5>
          <p>举办无人发布会，主讲人是 CEO 的柴犬 NFT，全场 0 bug，0 人。</p>
        </div>
      </div>
      <div class="item">
        <img src="/a_6.jpg" alt="" />
        <div>
          <h5>小小暖宝,温暖地球</h5>
          <p>今年6月，向50℃的印度捐赠一百万个暖宝宝，此举感动印度总统。</p>
        </div>
      </div>
    </div>
  </section>
</article>

<style>
  @import "tailwindcss";
  article *,
  article {
    @apply m-2 text-sm;
  }
  article {
    @apply flex flex-col gap-4;
  }
  article h3 {
    @apply text-zinc-500 text-2xl;
  }
  article h4 {
    @apply text-lg;
  }
  article section {
    @apply m-0 px-3;
  }
  .hscroll-container {
    @apply flex flex-row overflow-x-scroll;
    scroll-snap-type: x mandatory;
  }
  .hscroll-container .item {
    @apply w-70 h-70 shrink-0
    relative overflow-clip shadow;
    scroll-snap-align: center;
  }
  .hscroll-container .item * {
    @apply p-0 m-0;
  }
  .hscroll-container .item img {
    @apply w-full h-3/5 object-cover;
  }
  .hscroll-container .item div {
    @apply block w-full h-2/5 p-3;
  }
  .hscroll-container .item div h5 {
    @apply text-lg mb-2 text-zinc-500;
  }
</style>
