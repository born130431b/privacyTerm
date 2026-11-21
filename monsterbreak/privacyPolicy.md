# Monster Break: You Defend! 개인정보 처리방침

[한국어](#한국어) · [English](#english) · [简体中文](#简体中文) · [日本語](#日本語)

## 한국어

**개인정보 처리방침**

**시행일 2026년 11월 21일** · 개인정보처리자 및 개인정보 보호 담당자 **Maybe My Studio 이성진** · [개인정보 문의](mailto:maybemyportfolio@gmail.com)

### 1. 게스트 플레이와 기기 저장

Google 계정 없이 모든 라운드를 플레이할 수 있습니다. 라운드, 골드, 강화 상태는 한 판이 진행되는 동안 기기 메모리에서 처리됩니다. 새 게임을 시작하면 초기화되며, Google 로그인으로 백업하거나 다른 기기로 옮길 수 없습니다. 음소거 설정은 다음 실행에도 적용되도록 기기에 저장하며, 앱 데이터를 지우면 초기화됩니다.

### 2. Android에서 Google 로그인을 선택할 때

준비 화면의 **계정**에서 Google 계정을 선택하면 Android의 계정 선택기를 통해 발급된 Google ID 토큰을 Firebase Authentication으로 전송합니다. 첫 로그인 때 이 게임의 Firebase 계정이 생성됩니다. 계정을 식별하고 로그인을 유지하기 위해 Google 계정 식별자, Firebase 사용자 식별자(UID), 인증 토큰, Google에서 제공하는 이메일 주소와 기본 프로필 정보(표시 이름, 제공되는 경우 프로필 사진 주소)를 처리할 수 있습니다. 게임의 계정 화면에는 인증된 표시 이름이 나옵니다. Google 계정 비밀번호는 게임에서 입력받지 않습니다.

인증 SDK는 세션 정보를 기기에 보관해 다음 실행 때 로그인을 복원합니다. 인증 요청 시 IP 주소, 앱 식별정보, 기기 플랫폼·SDK 버전 등의 기술 정보를 처리해 요청을 전달하고 부정 이용을 방지합니다. [Firebase Android SDK의 데이터 처리 안내](https://firebase.google.com/docs/android/play-data-disclosure)

### 3. 인증 처리 위탁과 국외 이전

운영자는 이용자가 요청한 계정 기능을 제공하는 데 필요한 범위에서 인증 처리를 Google(Firebase Authentication)에 위탁합니다. 한국 이용자의 인증정보 국외 위탁·보관은 개인정보 보호법 제28조의8 제1항 제3호 가목에 근거합니다.

| 항목 | 내용 |
| --- | --- |
| 이전받는 자·국가 | Google(Firebase Authentication), 미국. [Google 개인정보 문의](https://firebase.google.com/support/privacy/dpo) |
| 항목·목적 | 위 2항의 계정·인증 및 기술 정보. 계정 생성·인증, 세션 유지 및 부정 이용 방지 |
| 시점·방법 | Google 로그인 또는 기존 세션의 인증·갱신이 필요할 때 기기에서 암호화된 네트워크 연결로 전송 |
| 보유기간 | Firebase는 기록한 IP 주소를 수 주간 보관합니다. 그 밖의 인증정보는 게임 계정 삭제를 시작할 때까지 보관하며, 삭제 개시 후 180일 이내에 운영 시스템과 백업에서 제거합니다. [Firebase 보유기간 안내](https://firebase.google.com/support/privacy) |
| 거부 방법·영향 | Google 로그인을 선택하지 않고 게스트로 모든 라운드를 이용할 수 있습니다. 이미 로그인한 경우 **내 계정 → 로그아웃**으로 이 기기의 세션을 종료할 수 있습니다. 기존 계정 삭제 방법은 5항에 있습니다. |

### 4. 도입 예정인 Unity LevelPlay 보상형 광고

현재 버전에는 보상형 광고가 없습니다. 향후 패배한 뒤 이용자가 광고를 보고 한 번 더 도전할 수 있는 기능을 제공할 예정입니다. 시청 여부는 이용자가 선택하며 광고를 건너뛰고 새 게임을 시작할 수 있습니다.

광고 도입 후에는 Unity LevelPlay와 실제 광고를 제공하는 네트워크가 광고를 준비하거나 표시할 때 IP 주소 및 이를 통해 추정한 대략적인 지역, 사용 가능한 광고 식별자, 기기·앱 정보, 광고 요청·노출·클릭·시청 완료 여부를 처리할 수 있습니다. 목적은 광고 제공, 성과 측정, 부정 이용 방지 및 보상 확인입니다. 시청을 선택하기 전에도 광고를 미리 불러오는 과정에서 일부 정보가 전송될 수 있습니다. 맞춤 광고에 별도 동의가 필요한 지역에서는 먼저 동의를 받으며, 시청 선택은 맞춤 광고 동의와 별개입니다. 기기의 광고 개인정보 설정에서 광고 식별자 사용을 관리할 수 있습니다. 도입 전에 실제 광고 네트워크, 처리·이전 국가, 보유기간 및 거부 방법을 이 방침에 반영합니다. [Unity 게임 이용자 개인정보처리방침](https://unity.com/legal/game-player-and-app-user-privacy-policy)

<a name="계정-삭제"></a>

### 5. 게임 계정 삭제와 이용자 권리

**게임 계정을 삭제하려면** 연결한 Google 이메일 주소에서 아래 문의처로 게임 이름과 삭제 요청을 보내 주세요. 해당 주소에 접근할 수 없다면 연락 가능한 주소로 문의해 주세요. 비밀번호나 인증 코드를 보내실 필요는 없습니다. 운영자는 필요한 범위에서 본인을 확인한 뒤 게임의 Firebase 계정 삭제를 시작하고 처리 결과를 안내합니다. 로그아웃이나 앱 제거 후에도 서버 계정은 남습니다. 게임 계정을 삭제해도 Google 계정 자체는 계속 사용할 수 있습니다. [계정 삭제 요청 메일 보내기](mailto:maybemyportfolio@gmail.com?subject=Monster%20Break%20-%20Account%20deletion)

이용자 또는 법정대리인은 개인정보 열람, 정정, 삭제, 처리정지나 동의 철회를 요청할 수 있습니다. 만 14세 미만 아동의 개인정보 처리에 동의가 필요한 경우에는 법정대리인의 동의가 필요합니다. 동의 없이 처리되었다고 생각하시면 같은 주소로 알려 주세요. 한국에서는 개인정보침해 신고센터(118) 또는 개인정보분쟁조정위원회(1833-6972)에도 도움을 요청할 수 있습니다. [침해 신고](https://privacy.kisa.or.kr) · [분쟁조정](https://www.kopico.go.kr)

### 6. 문의 기록, 보호조치와 변경

운영자는 답변과 권리 요청 처리를 위해 발신 이메일 주소, 문의 내용 및 이용자가 보낸 첨부자료를 처리합니다. 처리가 끝나면 지체 없이 삭제하며, 법령상 보존 의무나 진행 중인 분쟁이 있는 경우 필요한 기록만 해당 사유가 끝날 때까지 보관한 뒤 삭제합니다. 운영자는 계정과 문의 기록에 대한 접근을 업무상 필요한 범위로 제한하고, 보유 목적이 끝난 전자기록을 복구하기 어려운 방법으로 삭제합니다. 법률상 근거나 별도 동의 없이 이용자의 개인정보를 제3자의 독자적인 목적으로 제공하지 않습니다.

방침이 바뀌면 변경 내용과 시행일을 이 페이지에 공지하며, 법령에 따라 별도 고지나 동의가 필요한 경우 해당 절차를 거칩니다. [문의 및 권리 행사 — maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)

---

## English

**Privacy Policy**

**Effective November 21, 2026** · Data controller and privacy contact: **Maybe My Studio, 이성진** · [Contact us](mailto:maybemyportfolio@gmail.com)

### 1. Guest play and data on your device

You can play every round without a Google account. During a match, your device keeps the round, gold and upgrades in memory. Starting a new match resets them. Google sign-in does not back them up or transfer them between devices. Your mute preference is saved on the device for your next session. Clearing the app’s data resets it.

### 2. Choosing Google sign-in on Android

When you choose a Google account from **Account** on the preparation screen, the game sends the Google ID token obtained through Android’s account picker to Firebase Authentication. Your first sign-in creates a Firebase account for this game. To identify you and keep you signed in, the service may process your Google account identifier, Firebase user ID (UID), authentication tokens, and the email address and basic profile information Google supplies (display name and profile photo URL, if available). The game’s account screen shows your verified display name. The game does not ask for your Google password.

The authentication SDK stores session information on your device so it can restore your sign-in the next time you open the game. During authentication it processes technical information such as your IP address, app identifiers, device platform and SDK version to handle requests and prevent abuse. [Firebase Android SDK data disclosures](https://firebase.google.com/docs/android/play-data-disclosure)

### 3. Who processes sign-in data and where

The operator uses Google (Firebase Authentication) to provide the account feature you request. For users in South Korea, the legal basis for outsourcing authentication and storing the data overseas is Article 28-8(1)3(a) of the Personal Information Protection Act.

| Item | Details |
| --- | --- |
| Recipient and location | Google (Firebase Authentication), United States. [Google privacy inquiries](https://firebase.google.com/support/privacy/dpo) |
| Data and purpose | The account, authentication and technical data in section 2, used to create and authenticate your account, maintain sessions and prevent abuse. |
| When and how | Your device sends the data over an encrypted connection when you sign in or an existing session needs verification or renewal. |
| Retention | Firebase keeps logged IP addresses for a few weeks. It keeps other authentication data until deletion of the game account is initiated, then removes it from its live systems and backups within 180 days. [Firebase retention information](https://firebase.google.com/support/privacy) |
| Your choice | Skip Google sign-in to play every round as a guest. If already signed in, choose **My Account → Sign out** to end the session on this device. Section 5 explains how to delete an existing account. |

### 4. Planned Unity LevelPlay rewarded ads

The current version has no rewarded ads. We plan to offer a choice after a defeat: watch an ad for another chance or skip it and start a new game.

Once this feature is available, Unity LevelPlay and the networks serving the ads may process your IP address and approximate location inferred from it, available advertising identifiers, device and app details, and ad requests, impressions, clicks and completion events. They use this information to deliver and measure ads, prevent fraud and confirm rewards. Some information may be sent when an ad is preloaded, before you choose whether to watch. Where separate consent is required for personalized ads, we will ask first. Choosing to watch an ad is a separate decision. You can manage your advertising identifier in your device’s ad privacy settings. Before enabling ads, we will update this policy with the networks used, countries of processing or transfer, retention periods and ways to opt out. [Unity’s Game Player and App User Privacy Policy](https://unity.com/legal/game-player-and-app-user-privacy-policy)

<a name="delete-game-account"></a>

### 5. Delete your game account or exercise your rights

**To delete your game account**, email us from the Google email address linked to the game. Include the game title and ask us to delete the account. If you have lost access to that address, write from an address where we can reach you. Please keep passwords and verification codes out of your message. We will verify account ownership as needed, initiate deletion of the game’s Firebase account and tell you the outcome. Signing out or uninstalling leaves the server account in place. Deleting the game account leaves your Google account available to you. [Email an account deletion request](mailto:maybemyportfolio@gmail.com?subject=Monster%20Break%20-%20Account%20deletion)

You or your legal representative can request access, correction, deletion or restriction of processing, or withdraw consent. Where consent is required to process the data of a child under 14 in South Korea, the child’s legal representative must give it. Contact us if you believe such data was processed without that consent. In South Korea you can also contact the Privacy Infringement Report Center (118) or the Personal Information Dispute Mediation Committee (1833-6972). [Report an infringement](https://privacy.kisa.or.kr) · [Dispute mediation](https://www.kopico.go.kr)

### 6. Support records, safeguards and policy changes

We use your sender address, message and any attachments you provide to answer inquiries and handle rights requests. We delete them without undue delay when the matter is closed. If a law requires retention or a dispute is ongoing, we keep only the necessary records until that obligation or dispute ends, then delete them. We restrict access to account and support records to those who need it for their work and erase electronic records in a way that makes recovery difficult once the purpose is fulfilled. We only disclose personal data to third parties for their own purposes if there is a legal basis or separate consent.

We will post changes and their effective date on this page and provide separate notice or seek consent when the law requires it. [Privacy and rights requests — maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)

---

## 简体中文

**隐私政策**

**生效日期：2026 年 11 月 21 日** · 个人信息处理者及隐私事务联系人：**Maybe My Studio，이성진** · [联系我们](mailto:maybemyportfolio@gmail.com)

### 1. 游客模式与设备上的数据

无需 Google 账号即可游玩所有回合。每局的回合进度、金币和强化状态保存在设备内存中，开始新的一局后会重置。Google 登录不提供进度备份或跨设备转移功能。静音设置保存在本机，下次启动时仍然有效。清除应用数据即可重置该设置。

### 2. 在 Android 上选择 Google 登录

在备战界面的**账号**菜单中选择 Google 账号后，游戏会将通过 Android 账号选择器取得的 Google ID 令牌发送给 Firebase Authentication。首次登录会为本游戏创建一个 Firebase 账号。为了识别账号并维持登录状态，认证服务可能处理 Google 账号标识符、Firebase 用户标识符（UID）、认证令牌，以及 Google 提供的电子邮箱和基本资料（显示名称，以及如有提供的头像网址）。游戏的账号界面会显示经认证的显示名称。游戏不会要求您输入 Google 密码。

认证 SDK 将会话信息保存在设备上，以便下次打开游戏时恢复登录。处理认证请求时，SDK 会处理 IP 地址、应用标识、设备平台和 SDK 版本等技术信息，用于处理请求和防止滥用。[Firebase Android SDK 数据处理说明](https://firebase.google.com/docs/android/play-data-disclosure)

### 3. 认证服务的受托方与跨境传输

为提供您选择的账号功能，运营者委托 Google（Firebase Authentication）处理认证。对于韩国用户，委托境外处理和存储认证数据的依据为韩国《个人信息保护法》第 28 条之 8 第 1 款第 3 项第 1 目（가목）。

| 项目 | 说明 |
| --- | --- |
| 接收方及处理国家 | Google（Firebase Authentication），美国。[向 Google 咨询隐私问题](https://firebase.google.com/support/privacy/dpo) |
| 数据及目的 | 第 2 节所列的账号、认证及技术信息，用于创建和验证账号、维持会话以及防止滥用。 |
| 时间及方式 | 登录、验证或更新现有会话时，设备通过加密网络连接发送数据。 |
| 保存期限 | Firebase 将记录的 IP 地址保存数周。其他认证信息保存至游戏账号删除程序启动，随后在 180 天内从在线系统和备份中移除。[Firebase 保存期限说明](https://firebase.google.com/support/privacy) |
| 您的选择 | 您可以跳过 Google 登录，以游客身份游玩所有回合。已登录时，可在**我的账号 → 退出登录**结束本设备的会话。删除已有账号的方法见第 5 节。 |

### 4. 计划推出的 Unity LevelPlay 激励广告

当前版本尚未提供激励广告。我们计划在玩家落败后提供一次选择：观看广告获得再次挑战的机会，或跳过广告开始新的一局。

功能上线后，Unity LevelPlay 和实际投放广告的广告网络在准备或展示广告时，可能处理 IP 地址及据此推断的大致位置、可用的广告标识符、设备与应用信息，以及广告请求、展示、点击和观看完成情况。处理目的是投放广告、衡量效果、防范欺诈和确认奖励。预加载广告时，部分信息可能会在您选择是否观看之前发送。在个性化广告需要单独同意的地区，我们将事先征求同意。选择观看广告与同意个性化广告是两个独立的选择。您可以通过设备的广告隐私设置管理广告标识符。广告启用前，我们将更新本政策，列明实际使用的广告网络、处理或传输所涉及的国家、保存期限及拒绝方式。[Unity 游戏玩家与应用用户隐私政策](https://unity.com/legal/game-player-and-app-user-privacy-policy)

<a name="删除游戏账号"></a>

### 5. 删除游戏账号及行使个人信息权利

**如需删除游戏账号**，请使用与游戏关联的 Google 邮箱联系我们，注明游戏名称并提出删除请求。如果无法使用该邮箱，请使用我们能联系到您的其他邮箱。请勿发送密码或验证码。我们会进行必要的身份核验，启动本游戏 Firebase 账号的删除程序，并告知处理结果。退出登录或卸载应用后，服务器上的账号仍会保留。删除游戏账号后，您仍可使用原来的 Google 账号。[发送账号删除请求](mailto:maybemyportfolio@gmail.com?subject=Monster%20Break%20-%20Account%20deletion)

您或您的法定代理人可以要求查阅、更正、删除个人信息，要求限制处理，或撤回同意。在韩国，如处理未满 14 周岁儿童的个人信息需要同意，则须由其法定代理人同意。如果您认为此类信息在未获得同意的情况下被处理，请联系我们。在韩国，也可向个人信息侵害举报中心（118）或个人信息纠纷调解委员会（1833-6972）求助。[侵权举报](https://privacy.kisa.or.kr) · [纠纷调解](https://www.kopico.go.kr)

### 6. 咨询记录、保护措施与政策变更

我们使用您的发件邮箱、来信内容及您主动提供的附件来答复咨询、处理权利请求。事项办结后，我们会及时删除相关信息。如法律要求留存或争议仍在处理中，我们仅保留必要记录，直至留存义务或争议结束后再予删除。只有因工作需要的人员才能访问账号和咨询记录。处理目的实现后，我们采用难以恢复的方式删除电子记录。仅在有法律依据或取得单独同意时，我们才会向第三方提供个人信息供其用于自身目的。

本政策变更时，我们将在此页公布变更内容和生效日期，并在法律要求时另行通知或征得同意。[隐私咨询和权利请求 — maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)

---

## 日本語

**プライバシーポリシー**

**施行日　2026年11月21日** · 個人情報の取扱事業者・お問い合わせ担当者　**Maybe My Studio　이성진** · [お問い合わせ](mailto:maybemyportfolio@gmail.com)

### 1. ゲストプレイと端末に保存される情報

Google アカウントがなくても、すべてのラウンドをプレイできます。ラウンドの進行状況、ゴールド、強化の状態は、対戦中に端末のメモリで管理され、新しい対戦を始めるとリセットされます。Google ログインによる進行状況のバックアップや端末間の引き継ぎには対応していません。ミュート設定は次回の起動時にも適用されるよう端末に保存されます。アプリデータを消去すると設定はリセットされます。

### 2. Android で Google ログインを選んだとき

準備画面の**アカウント**から Google アカウントを選ぶと、Android のアカウント選択画面を通じて取得した Google ID トークンが Firebase Authentication に送信されます。初回ログイン時に、このゲーム専用の Firebase アカウントが作成されます。アカウントの識別とログイン状態の維持のため、Google アカウントの識別子、Firebase ユーザー ID（UID）、認証トークン、Google が提供するメールアドレスと基本プロフィール（表示名および提供される場合はプロフィール画像の URL）を取り扱うことがあります。ゲームのアカウント画面には、認証済みの表示名が表示されます。ゲーム内で Google のパスワードを入力する必要はありません。

認証 SDK はセッション情報を端末に保存し、次回起動時にログイン状態を復元します。認証時にはリクエストの処理と不正利用の防止のため、IP アドレス、アプリの識別情報、端末のプラットフォーム、SDK のバージョンなどの技術情報を取り扱います。[Firebase Android SDK のデータ開示情報](https://firebase.google.com/docs/android/play-data-disclosure)

### 3. 認証の委託先と国外移転

運営者は、ご希望のアカウント機能を提供するため、認証処理を Google（Firebase Authentication）に委託します。韓国の利用者に関する認証情報の国外での取扱いの委託・保管は、韓国の個人情報保護法第28条の8第1項第3号イ（가목）に基づきます。

| 項目 | 内容 |
| --- | --- |
| 移転先・取扱国 | Google（Firebase Authentication）、米国。[Google のプライバシー窓口](https://firebase.google.com/support/privacy/dpo) |
| 対象情報・目的 | 第2項のアカウント情報、認証情報、技術情報。アカウントの作成と認証、セッションの維持、不正利用の防止に用います。 |
| 時期・方法 | ログイン時、または既存セッションの確認・更新時に、端末から暗号化された通信で送信します。 |
| 保管期間 | Firebase は記録した IP アドレスを数週間保管します。その他の認証情報はゲームアカウントの削除手続きの開始まで保管し、その後180日以内に稼働中のシステムおよびバックアップから消去します。[Firebase の保管期間](https://firebase.google.com/support/privacy) |
| 利用者の選択 | Google ログインを選ばず、ゲストとしてすべてのラウンドをプレイできます。ログイン済みの場合は、**マイアカウント → ログアウト**でこの端末のセッションを終了できます。アカウントの削除方法は第5項をご覧ください。 |

### 4. 導入予定の Unity LevelPlay リワード広告

現在のバージョンではリワード広告を配信していません。今後、敗北後に、広告を視聴してもう一度挑戦するか、視聴せずに新しい対戦を始めるかを選べる機能を導入する予定です。

導入後は、Unity LevelPlay と実際に広告を配信する広告ネットワークが、広告の準備・表示時に、IP アドレスとそこから推定されるおおよその地域、利用可能な広告識別子、端末・アプリ情報、広告のリクエスト・表示・クリック・視聴完了に関する情報を取り扱う場合があります。広告の配信、効果測定、不正防止、報酬の確認のために利用します。広告の事前読み込みに伴い、視聴を選ぶ前に一部の情報が送信される場合があります。パーソナライズ広告に個別の同意が必要な地域では、事前に同意を求めます。広告を視聴するかどうかは別に選択できます。広告識別子は端末の広告プライバシー設定で管理できます。広告の配信開始前に、実際の広告ネットワーク、取扱国・移転先の国、保管期間、拒否方法を本方針に掲載します。[Unity のゲームプレイヤーおよびアプリユーザー向けプライバシーポリシー](https://unity.com/legal/game-player-and-app-user-privacy-policy)

<a name="ゲームアカウントの削除"></a>

### 5. ゲームアカウントの削除と利用者の権利

**ゲームアカウントの削除をご希望の方**は、連携した Google メールアドレスから、ゲーム名と削除を希望する旨をお知らせください。そのアドレスを使えない場合は、返信を受け取れる別のアドレスからご連絡ください。パスワードや確認コードは送らないでください。必要な範囲でご本人であることを確認し、このゲームの Firebase アカウントの削除手続きを開始して結果をお知らせします。ログアウトやアプリのアンインストール後も、サーバー上のアカウントは残ります。ゲームアカウントを削除した後も Google アカウント自体は利用できます。[アカウントの削除をメールで依頼](mailto:maybemyportfolio@gmail.com?subject=Monster%20Break%20-%20Account%20deletion)

利用者または法定代理人は、個人情報の開示・訂正・削除・利用停止を求め、または同意を撤回できます。韓国では、14歳未満の子どもの個人情報を同意に基づき取り扱う場合、法定代理人の同意が必要です。同意を得ずに取り扱われたと思われる場合はご連絡ください。韓国では、個人情報侵害申告センター（118）または個人情報紛争調停委員会（1833-6972）にも相談できます。[侵害の申告](https://privacy.kisa.or.kr) · [紛争調停](https://www.kopico.go.kr)

### 6. 問い合わせ記録、安全管理、方針の変更

運営者は、お問い合わせへの回答や権利行使への対応のため、送信元メールアドレス、本文、ご自身で添付した資料を利用します。対応終了後は遅滞なく削除します。法令による保存義務や継続中の紛争がある場合は、必要な記録に限ってその事由がなくなるまで保管し、その後削除します。アカウント情報や問い合わせ記録へのアクセスは、業務上必要な人に限ります。保管目的を達した電子記録は復元が困難な方法で消去します。第三者が自らの目的で利用するための個人情報の提供は、法的根拠または個別の同意がある場合に限ります。

本方針を改定する場合は、変更内容と施行日をこのページに掲載し、法令上必要なときは個別の通知や同意取得を行います。[プライバシーに関するお問い合わせ・権利行使 — maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)
