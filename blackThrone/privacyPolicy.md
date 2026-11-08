# 검은 왕좌 · BLACK THRONE 개인정보처리방침

작성·갱신일: 2026년 11월 8일  
문서 상태: 개발·테스트 버전 기준 안내 및 공개 서비스 전 검토용 초안

- 게임: 검은 왕좌 · BLACK THRONE
- 운영 명칭: Maybe My Studio
- 개인정보처리자 및 개인정보 보호 담당자: 이성진(개인 개발자·운영자)
- 개인정보 문의·권리 행사·계정 삭제 요청: [maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)
- 관련 문서: [게임 이용약관 및 에셋·음원 출처](TermsOfUse)

이 방침은 이 게임의 기기 내 저장, 선택적 Google 로그인·클라우드 백업, 광고 및 문의 처리에 적용됩니다. 로그인과 광고는 Android 연동 코드 및 서비스 구성을 기준으로 설명하며, 실제 기기의 로그인·광고·동의·복귀 흐름 전체 검증은 아직 완료되지 않았습니다. 이 문서를 게시했다는 사실이 스토어 출시, 서비스의 상시 제공 또는 공개 서비스의 법적·기술적 준비 완료를 뜻하지 않습니다.

## 1. 처리하는 정보와 목적

| 구분 | 정보 항목 | 목적 및 발생 조건 |
|---|---|---|
| 기기 내 게임 저장 | 조각 보유량, 스킬 해금·강화·장착 상태, 최대 3개의 이어하기, 여정 식별자(runId), 레벨·진행 및 광고 부활 사용 상태, 전투 적응에 필요한 게임 통계, 앱에서 생성한 기기별 무작위 식별자·변경 순번, 저장 생성·갱신 시각, 처치·보상 중복 방지 기록, 저장 변경 식별자·버전 | 진행 유지, 중복 보상 방지, 다음 교전의 게임 규칙 적용. 게스트 플레이도 기기에 저장됩니다. |
| 기기 내 설정 | 효과음·화면 흔들림 등 제공되는 표시·입력 설정 | 설정 유지. 모든 설정이 클라우드에 백업되는 것은 아닙니다. |
| 선택적 Google 로그인 | Google 인증 결과·ID 토큰, Firebase 사용자 식별자(UID), 로그인 제공자 정보. Google/Firebase 인증 시스템에서 계정 이메일·이름·프로필 사진 등 기본 계정 정보와 IP 주소·사용자 에이전트가 처리될 수 있음 | 이용자가 로그인할 때 본인 계정 인증 및 계정별 저장 분리. 게임 진행 백업에는 UID를 사용하며 이메일·이름·사진을 별도 게임 프로필 필드로 복제하지 않습니다. Google 비밀번호를 게임이 직접 입력받거나 보관하지 않습니다. |
| 선택적 클라우드 백업 | UID와 해당 계정의 게임 프로필, 조각·스킬·이어하기·부활 사용 상태, 기기별 무작위 식별자·변경 순번, 저장 시각·처치 기록, 변경 식별자·저장 버전 | 로그인한 계정의 진행 백업·복구, 충돌 확인, 중복 쓰기 방지. 앱 시작·계정 연결 시 조회하고 진행 변경 사건에 따라 저장하며, 매 프레임 전투 기록을 전송하지 않습니다. |
| 광고 SDK | IP 주소와 그로부터 추정되는 대략적 위치, 앱·광고 상호작용(실행·탭·영상 시청 등), 성능·진단 정보, Android 광고 ID·앱 세트 ID 등 기기·계정 식별자, 필요한 동의·개인정보 선택 상태 | 광고 요청·표시·측정, 보상 확인, 부정 사용 방지. Google Mobile Ads와 UMP가 실제 설정·지역·기기 및 이용자의 선택에 따라 처리합니다. |
| 문의 | 발신 이메일, 문의 내용, 이용자가 자발적으로 첨부한 자료 | 답변, 오류 확인, 권리 행사 및 계정 삭제 요청 처리 |

연락처 목록, 문자 내용, 마이크 녹음, 카메라 영상 또는 GPS를 통한 정확한 위치를 게임 기능으로 수집하지 않습니다. 별도 Google Analytics 또는 Firebase Crashlytics 분석·오류 수집 기능은 현재 구성에 도입하지 않았습니다. 이는 인증·광고 SDK 자체의 보안·진단 정보 처리가 없다는 뜻은 아닙니다.

문의 시 비밀번호·인증 토큰·결제 수단 전체 번호·신분증 등 불필요한 정보를 보내지 마십시오. 게임의 전투 적응은 게임 통계를 이용한 난이도·패턴 조정이며 이용자의 현실 신원이나 민감정보를 평가하는 기능이 아닙니다.

## 2. 선택 기능과 광고 개인정보 선택

Google 로그인은 선택 사항입니다. 로그인하지 않아도 로컬 전투를 이용할 수 있으나 계정 기반 클라우드 복구는 제한됩니다. 로그아웃은 계정이나 클라우드 자료의 삭제와 다릅니다.

보상형 광고는 이용자가 부활 또는 화면에 안내된 조각 보상을 선택하는 경우에 사용됩니다. 사망 후 화면 전환 시 전면광고가 표시될 수 있습니다. 보상형 광고를 선택하지 않았다는 사실만으로 전면광고 요청이나 광고 SDK의 모든 처리가 중단되는 것은 아닙니다.

광고 연동은 UMP에서 동의 정보를 갱신하고, 필요한 메시지를 표시하며, SDK가 광고 요청을 허용한 경우에만 광고를 요청하도록 구성되어 있습니다. 개인정보 선택 변경이 필요한 경우 게임 설정의 광고 개인정보 옵션을 이용할 수 있도록 연결되어 있습니다. 실제 제공 여부와 문구는 지역·플랫폼·SDK 상태에 따라 달라질 수 있습니다.

Android의 광고 개인정보 설정에서 광고 ID를 삭제하거나 관련 선택을 변경할 수 있습니다. 맞춤 광고 거부 또는 광고 ID 삭제가 모든 광고·보안·측정 정보 처리를 중단시키는 것은 아닙니다. 적용되는 법령상 동의가 필요한 처리에는 별도의 동의 절차가 필요하며, 게임 이용 또는 이 문서 열람만으로 모든 처리에 동의한 것으로 취급하지 않습니다.

## 3. 외부 서비스·위탁·제공

| 제공자·서비스 | 처리 업무 및 정보 범위 | 안내 |
|---|---|---|
| Google 로그인 / Firebase Authentication | 계정 인증, 인증 계정 정보·UID, 인증 통신 및 보안 정보 | [Google 개인정보처리방침](https://policies.google.com/privacy), [Firebase 개인정보·보안 안내](https://firebase.google.com/support/privacy) |
| Google Cloud Firestore | UID별 게임 프로필 보관·동기화 | 현재 프로젝트의 게임 진행 DB 리전은 대한민국 서울(asia-northeast3)입니다. |
| Google AdMob / Mobile Ads / UMP | 광고 송출·측정·보안, 개인정보 선택 관리 | [광고 SDK 데이터 공개 안내](https://developers.google.com/admob/android/privacy/play-data-disclosure), [UMP 안내](https://developers.google.com/admob/android/privacy) |
| 문의 이메일 서비스 | 문의 이메일·첨부 자료의 송수신·보관 | 문의에 이용하는 이메일 서비스의 정책도 적용됩니다. |
| GitHub 및 외부 출처 링크 사이트 | 정책·약관·출처 문서 열람 시 웹 접속 정보 | GitHub는 이 게임의 진행 DB가 아닙니다. 외부 링크를 열면 IP 주소·브라우저 정보 등이 해당 사이트 정책에 따라 처리될 수 있습니다. [GitHub 개인정보 안내](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) |

Firebase의 인증·저장 처리는 운영자를 위한 서비스 제공 업무에 해당하는 범위가 있으며, 광고 사업자의 처리 목적·법적 지위는 해당 서비스의 실제 계약·설정에 따라 구분됩니다. 이 표 전체를 일괄적으로 제3자 제공 동의나 처리 위탁 동의로 대신하지 않습니다. 법령에 따른 적법한 요청에 대응해야 하는 경우에는 필요한 범위에서 정보를 처리할 수 있습니다.

## 4. 국외 처리

게임 진행 DB의 서울 리전과 인증·광고 서비스의 처리 장소는 서로 다릅니다. Firebase 공식 안내에 따르면 Authentication은 미국 데이터센터에서 처리됩니다. Google의 광고 및 관련 글로벌 서비스는 Google 또는 그 대리인이 시설을 운영하는 국가에서 정보를 처리할 수 있으므로, 모든 정보가 국내에만 보관된다고 안내하지 않습니다.

공개 서비스 전 실제 계약상 수령 법인·연락처, 이전 국가, 이전 항목·목적·시기·방법·기간, 법적 근거, 필요한 동의와 거부 방법·영향을 서비스별로 확정해 고지해야 합니다. 현재 이 항목은 해당 세부 고지와 필요한 동의 절차를 완료한 것으로 표시하지 않습니다. Google 로그인·클라우드 기능을 이용하지 않으면 그 기능을 위한 인증·백업 전송은 이용하지 않을 수 있으며, 광고의 선택 범위는 제2항을 따릅니다.

## 5. 보관과 파기

- **로컬 진행·설정:** 이용자의 기기에서 앱 데이터가 삭제되거나 해당 저장을 삭제할 때까지 보관됩니다. 운영체제의 백업·복원 기능이나 다른 기기 사본은 별도로 남을 수 있습니다.
- **클라우드 게임 프로필:** 계정 기반 백업 제공에 필요한 동안 보관하며, 본인 확인을 거친 삭제 요청 또는 보관 목적 종료 시 삭제 대상으로 처리합니다. 앱 삭제·로그아웃·이어하기 한 칸 삭제는 전체 클라우드 계정 삭제와 다릅니다.
- **인증 정보:** Firebase 공식 안내상 인증 IP 로그는 수 주간 보관될 수 있으며, 다른 인증 정보는 운영자가 해당 사용자의 삭제를 시작할 때까지 유지됩니다. 삭제 개시 후 제공자의 운영·백업 시스템에서 제거되기까지 최대 180일이 걸릴 수 있습니다. 이는 게임 운영자가 모든 정보를 임의로 180일 보관한다는 뜻이 아닙니다.
- **광고·동의 정보:** 실제 SDK 설정, 이용자의 선택, Google의 해당 서비스 정책에 따른 기간 동안 처리됩니다. 게임 프로필 삭제가 광고 사업자의 모든 기록을 즉시 삭제하는 것은 아닙니다.
- **문의 기록:** 답변·분쟁 처리에 필요한 범위에서 보관합니다. 구체적인 운영 보관 기간과 메일·첨부·백업의 삭제 절차는 공개 서비스 전 확정해 안내합니다.
- 법령상 별도 보관 의무가 적용되는 경우 해당 정보·근거·기간을 구분해 보관하고, 다른 목적으로 이용하지 않습니다. 현재 제공하지 않는 유료 구매를 이유로 결제 기록을 수집하거나 보관한다고 안내하지 않습니다.

삭제 대상 전자 정보는 운영 중인 시스템에서 복구·재생되지 않도록 삭제하고, 제공자가 관리하는 백업·로그의 삭제는 해당 제공자의 절차를 따릅니다. 현재 공개 서비스용 백업 보관·주기적 파기 절차 전체가 검증 완료된 것은 아닙니다.

## 6. 권리 행사 및 계정·데이터 삭제 요청

이용자는 관련 법령에 따라 열람, 정정·삭제, 처리 정지, 동의 철회 등을 요청할 수 있습니다.

1. [maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)으로 제목에 **“검은 왕좌 계정·데이터 삭제 요청”** 또는 요청 종류를 적어 보내주십시오.
2. 게임명, 로그인에 사용한 이메일 또는 확인 가능한 게임 계정 식별 정보, 삭제 범위(클라우드 진행·게임 인증 계정·문의 자료 등)를 알려주십시오. 비밀번호나 ID 토큰은 보내지 마십시오.
3. 운영자는 계정 소유 확인에 필요한 최소 정보로 확인하고 요청 범위·처리 결과를 안내합니다. 법령상 요청을 제한하거나 일부 정보를 보관해야 한다면 그 사유·범위를 안내합니다.
4. 클라우드 프로필과 해당 게임의 Firebase 인증 계정은 구분하여 처리합니다. 이 요청은 이용자의 Google 계정 자체를 삭제하지 않습니다.
5. 기기 내 저장은 앱 데이터 삭제 등으로 별도 삭제해야 할 수 있습니다. 다른 기기에 남은 저장을 다시 업로드하면 새 데이터가 생성될 수 있으므로 삭제 처리 중에는 재동기화를 중단해 주십시오.

현재 앱에 전체 계정 삭제 전용 버튼이나 자동 삭제 처리가 구현되어 있다고 안내하지 않습니다. 위 이메일은 앱을 재설치하지 않고도 요청할 수 있는 외부 접수 경로입니다. 계정 생성 기능을 포함한 Google Play 공개 서비스에는 앱 내부 삭제 요청 경로 등 별도 요건이 있으므로, 이메일 안내만으로 그 요건이 모두 충족된 것은 아닙니다. 참고: [Google Play 계정 삭제 요건](https://support.google.com/googleplay/android-developer/answer/13327111).

## 7. 아동·청소년

어린이용 서비스로 임의 설정하거나 성인용 서비스로 임의 확정하지 않습니다. 이 게임의 출시 대상 연령·지역, 스토어 등급, 연령 확인·보호자 동의 및 광고 아동·청소년 설정은 공개 서비스 전 확정·검증해야 합니다. 다른 게임의 연령 정책을 이 게임에 그대로 적용하지 않습니다. 법정대리인 동의 등 별도 보호 절차가 필요한 이용자를 대상으로 하는 경우 필요한 절차를 먼저 마련합니다.

## 8. 안전성 확보와 음원·에셋

계정별 저장을 UID로 분리하고 인증된 계정의 프로필 접근을 제한하도록 구성되어 있습니다. 인증·클라우드·광고 SDK는 각 제공자가 안내하는 암호화된 통신을 이용합니다. 운영자는 접근 권한 제한과 계정 보안을 유지하고 필요한 개인정보 보호 조치를 적용해야 합니다. 이러한 구성 설명을 모든 보안 사고의 방지를 보장하는 표현으로 사용하지 않습니다.

배경음·효과음·캐릭터·이펙트·폰트는 앱에 포함된 파일을 기기에서 표시·재생합니다. 음원 재생 때문에 OpenGameArt, Kenney, itch.io 또는 음원 제작자에게 재생 기록·계정·게임 진행을 보내지 않습니다. 생성형 도구로 제작한 이미지는 제작 과정의 자산이며, 이용자의 플레이 데이터를 이미지 생성 서비스로 보내는 기능이 아닙니다. 외부 출처 사이트를 직접 여는 경우의 처리는 제3항과 구분됩니다.

## 9. 변경 및 문의

처리 목적·항목·제공자·연령 정책 등이 변경되면 이 문서에 변경일과 적용 내용을 표시하고 필요한 경우 게임의 공지·동의 절차를 제공합니다. 공개 서비스 시행일은 출시 구성과 남은 고지 사항을 확정한 후 별도로 안내합니다.

개인정보 보호 담당자: 이성진 / Maybe My Studio  
연락처: [maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)


---

# BLACK THRONE Privacy Policy (English)

Created / updated: November 8, 2026  
Document status: Information based on the development and test version; draft for review before public service

- Game: 검은 왕좌 · BLACK THRONE
- Operating name: Maybe My Studio
- Personal information controller and privacy contact: 이성진 (Lee Seong-jin, individual developer and operator)
- Privacy inquiries, rights requests, and account deletion: [maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)
- Related document: [Terms of Use and Asset / Audio Credits](TermsOfUse.md)

This policy applies to on-device storage, optional Google sign-in and cloud backup, advertising, and inquiry handling for this game. Descriptions of sign-in and advertising are based on the Android integration code and service configuration. End-to-end verification of sign-in, advertising, consent, and return-to-game flows on physical devices has not yet been completed. Publication of this document does not mean that the game has launched in a store, that services are continuously available, or that all legal and technical preparations for public service are complete.

## 1. Information Processed and Purposes

| Category | Information | Purpose and circumstances |
|---|---|---|
| On-device game saves | Shard balance; skill unlock, upgrade, and equipment status; up to three continue saves; run identifier (runId); level, progress, and ad-revival usage; gameplay statistics needed for combat adaptation; app-generated random per-device identifier and change sequence; save creation and update times; records preventing duplicate kill rewards; save change identifiers and versions | Maintaining progress, preventing duplicate rewards, and applying game rules to the next encounter. Guest progress is also saved on the device. |
| On-device settings | Available display and input settings, such as sound effects and screen shake | Retaining settings. Not all settings are backed up to the cloud. |
| Optional Google sign-in | Google authentication results and ID tokens, Firebase user identifier (UID), and sign-in provider information. Google/Firebase authentication systems may process basic account information such as email address, name, and profile picture, as well as IP address and user agent. | Authenticating the user's account when they sign in and separating saves by account. Progress backups use the UID; email, name, and profile picture are not copied into separate game-profile fields. The game does not directly request or store Google passwords. |
| Optional cloud backup | UID and the account's game profile; shards, skills, continue saves, and revival usage; random per-device identifier and change sequence; save times and kill records; change identifiers and save versions | Backing up and restoring signed-in account progress, checking conflicts, and preventing duplicate writes. Data is read at app startup or account connection and saved when progress changes; combat records are not transmitted every frame. |
| Advertising SDKs | IP address and approximate location inferred from it; app and ad interactions, such as launches, taps, and video views; performance and diagnostic information; device or account identifiers such as Android advertising ID and app set ID; required consent and privacy-choice status | Requesting, displaying, and measuring ads; confirming rewards; and preventing abuse. Google Mobile Ads and UMP process information according to the actual configuration, region, device, and user choices. |
| Inquiries | Sender's email address, inquiry content, and materials voluntarily attached by the user | Responding, investigating errors, and handling rights and account-deletion requests |

The game does not collect contact lists, text-message contents, microphone recordings, camera images, or precise GPS location as game features. Separate Google Analytics or Firebase Crashlytics analytics/error-collection features have not been introduced in the current configuration. This does not mean that authentication or advertising SDKs do not process their own security or diagnostic information.

Do not send unnecessary information such as passwords, authentication tokens, full payment-card or payment-method numbers, or identity documents when contacting us. Combat adaptation adjusts difficulty and patterns using gameplay statistics; it does not assess users' real-world identities or sensitive information.

## 2. Optional Features and Advertising Privacy Choices

Google sign-in is optional. Local combat is available without signing in, but account-based cloud recovery is limited. Signing out is different from deleting an account or cloud data.

Rewarded ads are used when users choose revival or the shard reward shown on screen. Interstitial ads may appear during screen transitions after death. Declining a rewarded ad does not, by itself, stop interstitial ad requests or all processing by advertising SDKs.

The ad integration is configured to update consent information through UMP, display required messages, and request ads only when the SDK permits ad requests. The game's settings are connected to advertising privacy options so that users can change privacy choices when required. Actual availability and wording may vary by region, platform, and SDK state.

Users can delete their advertising ID or change related choices in Android's advertising privacy settings. Opting out of personalized ads or deleting an advertising ID does not stop all advertising, security, or measurement processing. Processing that requires consent under applicable law requires a separate consent procedure; playing the game or reading this document is not treated as consent to all processing.

## 3. External Services, Entrusted Processing, and Disclosure

| Provider / service | Tasks and information scope | Information |
|---|---|---|
| Google sign-in / Firebase Authentication | Account authentication, authentication account information and UID, authentication communications and security information | [Google Privacy Policy](https://policies.google.com/privacy), [Firebase privacy and security](https://firebase.google.com/support/privacy) |
| Google Cloud Firestore | Storage and synchronization of game profiles by UID | The current project's game-progress database region is Seoul, Republic of Korea (asia-northeast3). |
| Google AdMob / Mobile Ads / UMP | Ad delivery, measurement, security, and privacy-choice management | [Advertising SDK data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure), [UMP information](https://developers.google.com/admob/android/privacy) |
| Inquiry email service | Sending, receiving, and storing inquiry emails and attachments | The policies of the email service used for inquiries also apply. |
| GitHub and linked external source websites | Web-access information when viewing policies, terms, or credit documents | GitHub is not the game's progress database. Opening external links may cause IP addresses, browser information, and other data to be processed under those sites' policies. [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) |

Firebase authentication and storage processing may constitute services performed on behalf of the operator within the applicable scope. Advertising providers' processing purposes and legal roles depend on their actual contracts and configurations. This table does not collectively replace consent to third-party disclosure or entrusted processing. Information may be processed to the extent necessary to respond to lawful requests under applicable law.

## 4. Processing Outside the Republic of Korea

The Seoul region of the game-progress database is separate from the processing locations of authentication and advertising services. According to Firebase's official information, Authentication is processed in US data centers. Google's advertising and related global services may process information in countries where Google or its agents operate facilities. We therefore do not state that all information remains in the Republic of Korea.

Before public service, service-specific disclosures must be finalized, including the actual contractual recipient entity and contact details, destination countries, transferred information, purposes, timing, methods, retention periods, legal grounds, and any required consent, refusal methods, and consequences. This section does not represent completion of those detailed disclosures or required consent procedures. Users who do not use Google sign-in or cloud features can avoid authentication and backup transfers for those features; advertising choices are described in Section 2.

## 5. Retention and Deletion

- **Local progress and settings:** Retained on the user's device until app data or the relevant save is deleted. Operating-system backups/restores or copies on other devices may remain separately.
- **Cloud game profiles:** Retained as needed to provide account-based backup and designated for deletion upon a verified deletion request or when the retention purpose ends. Uninstalling the app, signing out, or deleting one continue slot is different from deleting the entire cloud account.
- **Authentication information:** Firebase's official information states that authentication IP logs may be retained for a few weeks, while other authentication information remains until the operator initiates deletion of the user. Removal from the provider's operational and backup systems may take up to 180 days after deletion begins. This does not mean that the game operator arbitrarily retains all information for 180 days.
- **Advertising and consent information:** Processed for periods determined by actual SDK settings, user choices, and Google's applicable service policies. Deleting a game profile does not immediately delete every record held by an advertising provider.
- **Inquiry records:** Retained to the extent needed to answer inquiries and handle disputes. Specific operational retention periods and procedures for deleting emails, attachments, and backups will be finalized and disclosed before public service.
- Where a separate legal retention obligation applies, the relevant information, legal basis, and period will be identified, and the information will be retained separately and not used for other purposes. We do not claim to collect or retain payment records for paid purchases that are not currently offered.

Electronic information designated for deletion is deleted from operational systems so that it cannot be recovered or reproduced. Provider-managed backups and logs follow the provider's deletion procedures. The full public-service backup-retention and periodic-deletion procedures have not yet been verified.

## 6. Exercising Rights and Requesting Account / Data Deletion

Users may request access, correction or deletion, suspension of processing, withdrawal of consent, and other rights under applicable law.

1. Email [maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com) with **“BLACK THRONE Account / Data Deletion Request”** or the type of request in the subject.
2. Provide the game name, the email used to sign in or other verifiable game-account identification, and the scope of deletion requested, such as cloud progress, game authentication account, or inquiry materials. Do not send passwords or ID tokens.
3. The operator will verify ownership using the minimum necessary information and explain the scope and outcome. If a request must be restricted or some information retained under law, the reasons and scope will be explained.
4. The cloud profile and the game's Firebase authentication account are handled separately. This request does not delete the user's Google account itself.
5. On-device saves may need to be deleted separately, for example by clearing app data. Uploading a remaining save from another device may create new data, so please stop resynchronization while deletion is being processed.

We do not state that the current app has a dedicated full-account-deletion button or automated deletion process. The email address above is an external request channel that does not require reinstalling the app. Public Google Play services that include account creation are subject to additional requirements, including an in-app deletion-request route; providing an email address alone does not satisfy all such requirements. See [Google Play account deletion requirements](https://support.google.com/googleplay/android-developer/answer/13327111).

## 7. Children and Young People

We do not arbitrarily designate this as a children's service or definitively classify it as an adults-only service. Target ages and regions, store ratings, age verification, parental consent, and advertising settings for children and young people must be finalized and verified before public service. Another game's age policy is not automatically applied to this game. If the service targets users who require additional protections, such as consent from a legal representative, the necessary procedures will be established first.

## 8. Security Measures and Audio / Assets

Saves are separated by UID, and access to profiles is configured to be restricted to authenticated accounts. Authentication, cloud, and advertising SDKs use encrypted communications as described by their providers. The operator must maintain access restrictions and account security and apply necessary privacy safeguards. These configuration descriptions are not a guarantee that every security incident can be prevented.

Background music, sound effects, characters, effects, and fonts are displayed or played on the device from files included in the app. Audio playback does not send playback records, account information, or game progress to OpenGameArt, Kenney, itch.io, or audio creators. Images made with generative tools are production assets; they are not a feature that sends users' gameplay data to image-generation services. Processing when users directly open external source websites is separate and described in Section 3.

## 9. Changes and Contact

If processing purposes, information categories, providers, age policies, or other details change, this document will indicate the update date and applicable changes, and in-game notices or consent procedures will be provided where necessary. The public-service effective date will be announced separately after the release configuration and outstanding disclosures are finalized.

Privacy contact: 이성진 (Lee Seong-jin) / Maybe My Studio  
Email: [maybemyportfolio@gmail.com](mailto:maybemyportfolio@gmail.com)
