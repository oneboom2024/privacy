<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="author" content="kuma">
  <meta name="description" content="CardWorth Privacy Policy">
  <title>CardWorth Privacy Policy</title>
  <style>
    :root {
      color-scheme: light dark;
      --background: #f5f6f8;
      --surface: #ffffff;
      --text: #17191f;
      --muted: #626773;
      --border: #e3e5ea;
      --accent: #2864dc;
      --accent-soft: #eaf0ff;
      --shadow: 0 18px 55px rgba(25, 35, 55, 0.08);
    }

    @media (prefers-color-scheme: dark) {
      :root {
        --background: #101116;
        --surface: #191b22;
        --text: #f4f5f7;
        --muted: #adb2bd;
        --border: #2d3039;
        --accent: #79a5ff;
        --accent-soft: #202c48;
        --shadow: none;
      }
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      background: var(--background);
      color: var(--text);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
        "Helvetica Neue", Arial, "PingFang SC", "Hiragino Sans GB",
        "Microsoft YaHei", sans-serif;
      font-size: 16px;
      line-height: 1.72;
      -webkit-font-smoothing: antialiased;
    }

    a { color: var(--accent); }

    .page {
      width: min(920px, calc(100% - 32px));
      margin: 40px auto;
    }

    .card {
      padding: clamp(24px, 5vw, 58px);
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 24px;
      box-shadow: var(--shadow);
    }

    .toolbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 16px;
      margin-bottom: 34px;
    }

    .brand {
      font-size: 18px;
      font-weight: 750;
      letter-spacing: -0.01em;
    }

    .language-switcher {
      display: inline-flex;
      padding: 4px;
      background: var(--accent-soft);
      border-radius: 12px;
    }

    .language-switcher button {
      appearance: none;
      padding: 8px 13px;
      color: var(--muted);
      background: transparent;
      border: 0;
      border-radius: 9px;
      cursor: pointer;
      font: inherit;
      font-size: 14px;
      font-weight: 650;
    }

    .language-switcher button[aria-pressed="true"] {
      color: var(--text);
      background: var(--surface);
      box-shadow: 0 2px 8px rgba(25, 35, 55, 0.10);
    }

    h1 {
      margin: 0 0 8px;
      font-size: clamp(32px, 6vw, 48px);
      line-height: 1.12;
      letter-spacing: -0.035em;
    }

    h2 {
      margin: 34px 0 8px;
      font-size: 21px;
      line-height: 1.35;
      letter-spacing: -0.015em;
    }

    p { margin: 8px 0; }

    .effective-date,
    .summary,
    footer {
      color: var(--muted);
    }

    .summary {
      margin: 22px 0 30px;
      padding: 18px 20px;
      background: var(--accent-soft);
      border-radius: 14px;
    }

    footer {
      margin-top: 42px;
      padding-top: 24px;
      border-top: 1px solid var(--border);
      font-size: 14px;
    }

    [data-language] { display: none; }
    [data-language].active { display: block; }

    @media (max-width: 560px) {
      .page {
        width: 100%;
        margin: 0;
      }

      .card {
        min-height: 100vh;
        border: 0;
        border-radius: 0;
      }

      .toolbar {
        align-items: flex-start;
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <main class="page">
    <article class="card">
      <div class="toolbar">
        <div class="brand">CardWorth</div>
        <div class="language-switcher" role="group" aria-label="Language">
          <button id="language-en" type="button" aria-pressed="true">English</button>
          <button id="language-zh" type="button" aria-pressed="false">简体中文</button>
        </div>
      </div>

      <section data-language="en" class="active">
        <header>
          <h1>Privacy Policy</h1>
          <p class="effective-date">Effective date: August 14, 2026</p>
          <p class="summary">
            This Privacy Policy explains how OneBoom Media LIMITED collects,
            uses, shares and protects information when you use CardWorth.
          </p>
        </header>

        <h2>1. Information we process</h2>
        <p>
          We process account information such as your email address, sign-in
          provider identifier, nickname and profile photo. We also process card
          photographs you choose to submit, identified card details, collection
          records, grading requests, Pack Lens messages, app interactions,
          device and app identifiers, subscription product identifiers,
          purchase history and status, transaction identifiers, and crash
          diagnostics. We do not receive your complete payment-card details.
        </p>

        <h2>2. How we use information</h2>
        <p>
          We use information to authenticate your account, identify and grade
          cards, retrieve pricing information, save and synchronize your
          collection, provide subscription features, restore purchases,
          maintain security, prevent fraud, diagnose failures, improve
          CardWorth, analyze product usage, and measure advertising performance.
          We do not sell personal information.
        </p>

        <h2>3. Purchases and subscriptions</h2>
        <p>
          CardWorth subscriptions are processed by Apple through StoreKit and
          your App Store account. Apple handles payment information and
          determines the price and currency for your storefront. CardWorth
          receives product, transaction, subscription-status and entitlement
          information needed to complete purchases, unlock Pro features,
          prevent fraud and restore eligible purchases.
        </p>

        <h2>4. Analytics, advertising measurement and tracking</h2>
        <p>
          CardWorth uses Firebase Analytics and Firebase Crashlytics for product
          analytics and crash diagnostics, including services that may
          communicate with <code>google-analytics.com</code>. We use Meta App
          Events to measure app activity, trials, subscriptions and purchases
          and to understand advertising performance.
        </p>
        <p>
          App events may be sent without access to your advertising identifier.
          If you allow tracking through Apple’s App Tracking Transparency prompt,
          device identifiers and app-event data may also be used to measure
          advertising across apps and websites. You can change tracking
          permission at any time in iOS Settings.
        </p>

        <h2>5. Service providers</h2>
        <p>
          CardWorth uses Supabase for authentication, database, storage and
          server functions; Apple for Sign in with Apple and App Store
          subscriptions; CardSight for card identification and market data;
          Google Gemini for AI grading and Pack Lens responses; Google Firebase
          for analytics and crash diagnostics; and Meta for app-event and
          advertising measurement. Information is shared with these providers
          only as needed for the purposes described in this policy. Their
          processing is also governed by their own terms and privacy practices.
        </p>

        <h2>6. Card photographs and AI</h2>
        <p>
          Photos submitted for identification or grading may be transmitted to
          our processing providers. CardWorth does not use those photos for
          advertising. A card image URL and card details may be saved when you
          add an identified card to your collection. AI-generated grading and
          answers are estimates and may be inaccurate.
        </p>

        <h2>7. Storage and retention</h2>
        <p>
          Account, profile and collection data are kept while your account
          remains active. Temporary network files may be cached on your device
          and can be removed from Settings. Analytics, transaction, security
          and crash records are retained according to operational needs and the
          retention practices of the relevant providers. We may retain limited
          records when required for security, fraud prevention or legal
          compliance.
        </p>

        <h2>8. Your choices and deletion</h2>
        <p>
          You can edit your profile, remove cards, clear cached files, sign out,
          restore eligible purchases, or permanently delete your CardWorth
          account from Settings. You can manage subscriptions from your Apple
          account and control tracking permission in iOS Settings. Account
          deletion removes your CardWorth account and associated profile and
          collection records, subject to records we are legally required to
          retain. Apple purchase records are controlled by Apple and are not
          deleted with your CardWorth account.
        </p>

        <h2>9. Security and international processing</h2>
        <p>
          We use reasonable technical and organizational measures to protect
          information. No system can guarantee absolute security. Our providers
          may process information in countries different from your own, subject
          to safeguards available through those providers and applicable law.
        </p>

        <h2>10. Children</h2>
        <p>
          CardWorth is not intended for children below the minimum age required
          to consent to online services in their location. A parent or guardian
          should contact us if they believe a child has provided personal
          information without appropriate permission.
        </p>

        <h2>11. Changes and contact</h2>
        <p>
          We may update this policy as CardWorth changes. The effective date
          will be updated when material changes are made. For privacy questions
          or requests, visit <a href="https://oneboom.vip">oneboom.vip</a> or
          use the developer contact shown on CardWorth’s App Store product page.
        </p>
      </section>

      <section data-language="zh">
        <header>
          <h1>隐私政策</h1>
          <p class="effective-date">生效日期：2026 年 8 月 14 日</p>
          <p class="summary">
            本隐私政策说明 OneBoom Media LIMITED 在您使用 CardWorth 时如何收集、
            使用、共享和保护相关信息。
          </p>
        </header>

        <h2>1. 我们处理的信息</h2>
        <p>
          我们会处理电子邮箱、登录服务提供商标识符、昵称和头像等账户信息。
          我们还会处理您选择提交的卡牌照片、识别后的卡牌资料、收藏记录、评级请求、
          Pack Lens 消息、App 交互信息、设备和 App 标识符、订阅产品标识符、购买历史与状态、
          交易标识符以及崩溃诊断数据。我们不会接收您的完整银行卡或信用卡资料。
        </p>

        <h2>2. 信息的使用方式</h2>
        <p>
          我们使用相关信息来验证账户、识别和评级卡牌、获取价格信息、保存并同步收藏、
          提供订阅功能、恢复购买、维护安全、防止欺诈、诊断故障、改进 CardWorth、
          分析产品使用情况以及衡量广告效果。我们不会出售个人信息。
        </p>

        <h2>3. 购买与订阅</h2>
        <p>
          CardWorth 订阅由 Apple 通过 StoreKit 和您的 App Store 账户处理。
          Apple 负责处理付款信息，并根据您的 App Store 地区确定价格和货币。
          CardWorth 会接收完成购买、解锁 Pro 功能、防止欺诈及恢复有效购买所需的产品、
          交易、订阅状态和权益信息。
        </p>

        <h2>4. 分析、广告衡量与跟踪</h2>
        <p>
          CardWorth 使用 Firebase Analytics 和 Firebase Crashlytics 进行产品分析和崩溃诊断，
          相关服务可能会与 <code>google-analytics.com</code> 通信。我们使用 Meta App Events
          衡量 App 活动、试用、订阅和购买情况，并了解广告表现。
        </p>
        <p>
          在无法访问广告标识符的情况下，App 事件仍可能被发送。如果您通过 Apple 的
          “App 跟踪透明度”提示允许跟踪，设备标识符和 App 事件数据还可能用于衡量跨 App
          和网站的广告效果。您可以随时在 iOS“设置”中更改跟踪权限。
        </p>

        <h2>5. 服务提供商</h2>
        <p>
          CardWorth 使用 Supabase 提供身份验证、数据库、存储和服务器功能；使用 Apple
          提供“通过 Apple 登录”和 App Store 订阅；使用 CardSight 提供卡牌识别和市场数据；
          使用 Google Gemini 提供 AI 评级和 Pack Lens 回复；使用 Google Firebase 提供分析和
          崩溃诊断；使用 Meta 提供 App 事件和广告衡量。我们仅会在本政策所述目的所需范围内
          与这些提供商共享信息。相关处理也受各提供商自身条款和隐私政策约束。
        </p>

        <h2>6. 卡牌照片与 AI</h2>
        <p>
          用于识别或评级的照片可能会传输给我们的处理服务提供商。CardWorth 不会将这些照片
          用于广告。当您把已识别的卡牌加入收藏时，卡牌图片网址和卡牌资料可能会被保存。
          AI 生成的评级和回答仅为估算结果，可能并不准确。
        </p>

        <h2>7. 存储与保留</h2>
        <p>
          在账户保持有效期间，我们会保留账户、个人资料和收藏数据。临时网络文件可能缓存在
          您的设备上，并可在“设置”中清除。分析、交易、安全和崩溃记录会根据运营需要及相关
          服务提供商的保留规则保存。出于安全、防止欺诈或履行法律义务的需要，我们可能会保留
          有限的记录。
        </p>

        <h2>8. 您的选择与删除</h2>
        <p>
          您可以在“设置”中编辑个人资料、移除卡牌、清除缓存、退出登录、恢复有效购买或永久
          删除 CardWorth 账户。您可以通过 Apple 账户管理订阅，并在 iOS“设置”中控制跟踪权限。
          删除账户会移除 CardWorth 账户及相关个人资料和收藏记录，但法律要求保留的记录除外。
          Apple 的购买记录由 Apple 管理，不会随着 CardWorth 账户的删除而被删除。
        </p>

        <h2>9. 安全与跨境处理</h2>
        <p>
          我们采用合理的技术和组织措施保护信息，但任何系统都无法保证绝对安全。
          服务提供商可能会在您所在国家或地区之外处理信息，并遵守其提供的保障措施及适用法律。
        </p>

        <h2>10. 儿童隐私</h2>
        <p>
          CardWorth 不面向未达到其所在地同意使用在线服务最低年龄的儿童。如果家长或监护人
          认为儿童在未经适当许可的情况下提供了个人信息，请与我们联系。
        </p>

        <h2>11. 政策变更与联系我们</h2>
        <p>
          我们可能会随着 CardWorth 的变化更新本政策。如有重大变更，我们会更新生效日期。
          如有隐私相关问题或请求，请访问
          <a href="https://oneboom.vip">oneboom.vip</a>，或使用 CardWorth App Store
          产品页面上显示的开发者联系方式。
        </p>
      </section>

      <footer>
        <span lang="en">Official policy URL:</span>
        <span lang="zh-Hans">正式政策网址：</span>
        <a href="https://oneboom.vip/privacy/cardworth">https://oneboom.vip/privacy/cardworth</a>
      </footer>
    </article>
  </main>

  <script>
    (() => {
      const englishButton = document.getElementById("language-en");
      const chineseButton = document.getElementById("language-zh");
      const sections = document.querySelectorAll("[data-language]");

      function setLanguage(language) {
        document.documentElement.lang = language === "zh" ? "zh-Hans" : "en";
        sections.forEach((section) => {
          section.classList.toggle("active", section.dataset.language === language);
        });
        englishButton.setAttribute("aria-pressed", String(language === "en"));
        chineseButton.setAttribute("aria-pressed", String(language === "zh"));
      }

      englishButton.addEventListener("click", () => setLanguage("en"));
      chineseButton.addEventListener("click", () => setLanguage("zh"));

      const preferredLanguage = navigator.language.toLowerCase().startsWith("zh")
        ? "zh"
        : "en";
      setLanguage(preferredLanguage);
    })();
  </script>
</body>
</html>
