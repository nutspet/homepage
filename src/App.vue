<template>
  <main class="site-shell">
    <nav class="nav glass">
      <a class="brand" href="#home" aria-label="寻狗首页">
        <img src="/images/xungou-logo.png" alt="寻狗小程序 Logo" />
        <span>寻狗</span>
      </a>
      <div class="nav-links">
        <a href="#home">首页</a>
        <a href="#about">关于我们</a>
        <a href="#product">我们的产品</a>
        <a href="#team">团队成员</a>
      </div>
    </nav>

    <section id="home" class="hero section">
      <div class="orb orb-a"></div>
      <div class="orb orb-b"></div>
      <div class="hero-copy">
        <p class="eyebrow">科技 × 宠物 × AI</p>
        <h1>用智能连接线索，让每一次转发都更接近团圆。</h1>
        <p class="hero-text">
          寻狗是一套服务于微信生态的爱心小程序，覆盖寻狗启事、寻主启事、狗狗领养送养等场景。
          我们用数据化传播、AI 辅助匹配与轻量化工具，帮助走失狗狗更快回家，也让善意被更多人看见。
        </p>
        <div class="hero-actions">
          <a class="primary-btn" href="#product">查看产品入口</a>
          <a class="secondary-btn" href="#about">了解我们的使命</a>
        </div>
        <div class="metrics">
          <div>
            <strong>AI</strong>
            <span>线索聚合</span>
          </div>
          <div>
            <strong>微信</strong>
            <span>一键传播</span>
          </div>
          <div>
            <strong>爱心</strong>
            <span>助力回家</span>
          </div>
        </div>
      </div>
      <div class="hero-visual glass">
        <div class="signal-ring"></div>
        <img class="hero-logo" src="/images/xungou-logo.png" alt="寻狗 Logo" />
        <div class="ai-card card-top">AI 识别线索</div>
        <div class="ai-card card-bottom">附近扩散提醒</div>
      </div>
    </section>

    <section id="about" class="section split-section">
      <div>
        <p class="eyebrow">关于我们</p>
        <h2>把科技的精度，交给宠物回家的温度。</h2>
      </div>
      <div class="about-grid">
        <article class="feature-card">
          <span>01</span>
          <h3>科技驱动</h3>
          <p>用结构化启事、地理线索和传播入口，把原本分散的信息整理成更容易被看见、被转发、被回应的找寻网络。</p>
        </article>
        <article class="feature-card">
          <span>02</span>
          <h3>宠物友好</h3>
          <p>围绕狗狗走失、寻主、领养送养等真实场景设计流程，让主人、救助人和爱心用户都能快速参与。</p>
        </article>
        <article class="feature-card">
          <span>03</span>
          <h3>AI 辅助</h3>
          <p>持续探索 AI 在线索归类、图片信息提取、区域传播建议等能力中的应用，让每一条信息更有价值。</p>
        </article>
      </div>
    </section>

    <section id="product" class="section product-section">
      <div class="section-heading">
        <p class="eyebrow">我们的产品</p>
        <h2>在微信里搜索“寻狗”，让爱心入口触手可达。</h2>
        <p>
          用户可以通过微信搜一搜或扫码进入小程序，发布寻狗启事、转发传播卡片、查看附近线索，
          也可以参与寻主启事与狗狗领养送养信息的流转。
        </p>
      </div>
      <div class="product-layout">
        <div class="phone-card glass">
          <img src="/images/miniapp-screenshot.png" alt="寻狗小程序宣传截图" />
        </div>
        <div class="guide-card">
          <img src="/images/wechat-share-guide.png" alt="微信搜索寻狗与扫码入口推荐向导" />
          <div class="guide-copy">
            <h3>扫码或微信搜一搜</h3>
            <p>打开微信 / 发现 / 搜一搜，搜索“寻狗”，或识别二维码进入小程序，把需要帮助的狗狗信息扩散出去。</p>
          </div>
        </div>
      </div>
    </section>

    <section id="team" class="section team-section">
      <div class="section-heading">
        <p class="eyebrow">团队成员</p>
        <h2>保持神秘，也保持专注。</h2>
        <p>我们相信产品应该替团队说话。每一次稳定发布、每一条有效线索，都是幕后团队对爱心事业的认真投入。</p>
      </div>
      <article class="member-card glass">
        <div class="mystery-avatar">?</div>
        <div>
          <h3>舟哥</h3>
          <p>神秘技术负责人，专注把 AI、产品体验和爱心传播连接起来。</p>
        </div>
      </article>
    </section>

    <footer class="footer">
      <span>© 2026 寻狗 XUNGOU. 帮助狗狗回家，连接更多善意。</span>
      <a href="https://beian.miit.gov.cn/" target="_blank" rel="noreferrer">沪ICP备18044132号-1</a>
    </footer>
  </main>
</template>
