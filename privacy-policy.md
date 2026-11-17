# KnowGrove Privacy Policy

Last updated: November 17, 2026

This policy covers KnowGrove for iPhone, its share extension, and its Apple Watch companion. KnowGrove records audio, transcribes and organizes recordings on the device, and saves user-selected links or text as Markdown documents.

## Data Collection

KnowGrove does not automatically collect personal data for the developer. It does not create accounts, display ads, use third-party analytics SDKs, or track users across other companies' apps or websites. Recordings, transcripts, generated notes, and captured content are not uploaded to developer-operated servers or third-party AI servers for processing.

This does not mean that the app never uses a connection: purchases, paired-device transfers, user-selected file providers, external links, and support messages have the separate purposes described below.

## Microphone Access

With microphone permission, KnowGrove records when you start recording in the app, through a Shortcut, or on Apple Watch, including through a Watch quick-entry setting you have enabled. Audio is saved in the app's local storage. These recording features do not give the developer access to your audio. KnowGrove does not record phone-call audio.

## On-Device Transcription and Organization

Transcription, text organization, and summaries run on iPhone. The app can use available Apple on-device speech and language models, with bundled Whisper and Qwen models as local alternatives. The Apple speech path uses language resources already installed on the device; KnowGrove does not initiate model downloads. Model availability is also affected by the device and system settings.

Audio and text are not sent to an external AI service for these features. Transcripts and generated notes are stored locally and may be exported when you choose. AI output can contain recognition errors, omissions, or incorrect interpretations; check it against the original recording or text before relying on it.

## Apple Watch and Paired iPhone

The Watch companion records and stores audio on Apple Watch, then transfers recordings and session information to the paired iPhone using Apple's WatchConnectivity framework. When you request playback of an iPhone recording on Watch, the corresponding audio can also be transferred from the paired iPhone and stored on Watch. The devices also exchange recording ownership, deletion, and purchase-access information needed for the companion features. Transfers can wait until the devices can communicate. These transfers are between your paired devices, not to a developer-operated server. Transcription and organization run on iPhone, not on Apple Watch.

## Links, Text, and Share Extension

The Inbox saves links or text that you paste or share from another app. Capture processing happens on the device; it does not provide an embedded web browser or a public content feed. Each capture can be written as an independent Markdown document to a folder you explicitly select.

## Storage, Export, and Deletion

KnowGrove stores recordings, transcripts, generated notes, session information, preferences, and pending Inbox items in local app storage. It accesses folders you select to write, open, retry, or manage requested exports. A selected folder may be provided by iCloud Drive or another file provider. That provider may upload or synchronize exported files according to your settings and its own privacy practices. Opening an export in Obsidian or another app is also subject to that app's practices.

You can delete recordings or clear local records in Settings when no active operation prevents deletion. Deleting a recording sends a deletion request to the paired device; applying it there depends on communication with that device. For an individual recording, KnowGrove also attempts to remove its associated exported files when folder access and file-ownership checks permit it. This is not a guarantee that every external copy is deleted.

Clearing all local records or uninstalling the app does not remove files already exported to other folders, copies shared with other apps, or system or provider backups. Manage those copies and backups separately in the relevant app or service. Removing the iPhone app alone should not be treated as confirmation that data on Apple Watch has been deleted.

## Purchases and Trials

Purchases are processed by Apple through StoreKit and are associated with your App Store account. KnowGrove reads Apple's transaction and entitlement records on the device to determine purchase access and restore purchases. The developer does not receive payment-card details through the app.

Eligible new subscribers can start a seven-day free trial through Apple's purchase sheet. The monthly subscription renews automatically after the trial unless canceled beforehand in the Apple Account. A one-time lifetime purchase is also available. Apple manages pricing, eligibility, payment, and renewal. Older versions stored free-usage counters in the device Keychain; the current version no longer uses those counters to limit recording or capture. That legacy local data is not sent to the developer.

## Live Activities and Shortcuts

KnowGrove uses Apple Live Activities and App Shortcuts to show recording status and support user-initiated start and stop actions. These features do not transmit recording content to the developer.

## External Services and Support

The developer does not sell or rent your app content. User-initiated exports, file-provider synchronization, purchases, and external links may involve Apple or another service. The selected service's privacy practices apply to its own handling of information. This policy does not cover separate Obsidian plugins or other apps you choose to use with exported files.

If you choose to contact support by email or submit a GitHub issue, you provide the message and any attachments to the developer and the service you use. The developer uses that information to respond to and handle your request. GitHub issues are public. KnowGrove's support email link does not automatically attach recordings or diagnostics. Please do not send private recordings, sensitive captured content, or other information that is unnecessary for your request.

## Contact

For privacy or support questions, email [lufieu@gmail.com](mailto:lufieu@gmail.com). You can also submit a non-sensitive issue at:

https://github.com/lufie/KnowGrove-iOS-Support/issues

Do not include private recordings or sensitive captured content in a public issue.

---

# 言续隐私政策

更新日期：2026 年 11 月 17 日

本政策适用于言续 iPhone App、分享扩展和 Apple Watch 伴侣 App。言续用于录制音频、在设备端转录和整理录音，以及将用户选择的链接或文字保存为 Markdown 文档。

## 数据收集

言续不会为开发者自动收集个人数据，不创建账号、不展示广告、不使用第三方统计 SDK，也不跨其他公司的 App 或网站追踪用户。录音、转录、生成的笔记和收集内容不会上传到开发者运营的服务器或第三方 AI 服务器进行处理。

这不代表 App 完全不使用网络或设备连接：购买、配对设备传输、用户选择的文件提供商、外部链接和支持消息各有下文说明的用途。

## 麦克风访问

获得麦克风权限后，言续会在您通过 App、快捷指令或 Apple Watch 发起录音时录制，包括您已启用的 Watch 快捷入口自动录音。音频保存在 App 本地存储中。这些录音功能不会向开发者提供您的音频。言续不会录制电话通话音频。

## 设备端转录与整理

转录、文字整理和摘要在 iPhone 上运行。App 可以使用设备上可用的 Apple 端侧语音和语言模型，并以内置的 Whisper 和 Qwen 模型作为本地替代方案。Apple 语音路径仅使用设备上已安装的语言资源，言续不会主动发起模型下载。模型是否可用也受设备和系统设置影响。

这些功能不会将音频或文字发送给外部 AI 服务。转录和生成的笔记保存在本地，并可在您选择时导出。AI 结果可能存在识别错误、遗漏或理解偏差；使用前请与原始录音或文字核对。

## Apple Watch 与配对 iPhone

Watch 伴侣 App 在 Apple Watch 上录制和保存音频，再通过 Apple 的 WatchConnectivity 框架将录音和会话信息传输给配对的 iPhone。当您在 Watch 上请求播放 iPhone 中的录音时，对应音频也可以从配对 iPhone 传输并保存在 Watch 上。两端还会交换伴侣功能所需的录音归属、删除和购买权限信息。传输可能需要等待设备可以通信。这些传输发生在您的配对设备之间，不发送到开发者运营的服务器。转录和整理在 iPhone 上运行，不在 Apple Watch 上运行。

## 链接、文字与分享扩展

Inbox 保存您粘贴或从其他 App 分享的链接与文字。收集处理在设备本地完成，不提供内嵌网页浏览器或公开内容信息流。每次收集都可以作为独立 Markdown 文档写入您明确选择的文件夹。

## 存储、导出与删除

言续将录音、转录、生成的笔记、会话信息、偏好设置和等待处理的 Inbox 内容保存在 App 本地存储中。App 会为了执行您要求的写入、打开、重试或管理导出操作，访问您选择的文件夹。所选文件夹可能由 iCloud Drive 或其他文件提供商提供；提供商可能根据您的设置及其自身隐私规则上传或同步导出文件。在 Obsidian 或其他 App 中打开导出内容，也受该 App 自身的数据处理规则约束。

没有正在进行的操作阻止删除时，您可以删除录音或在设置中清空本地记录。删除录音会向配对设备发送删除请求；配对端何时执行取决于两端通信。对于单条录音，言续还会在文件夹访问权限和文件归属检查允许时，尝试移除其对应的导出文件。这不保证所有外部副本都被删除。

清空所有本地记录或卸载 App 不会移除已导出到其他文件夹的文件、分享给其他 App 的副本或系统及文件提供商的备份。请在相应 App 或服务中另行管理这些副本和备份。仅移除 iPhone App，也不应视为 Apple Watch 上的数据已经删除。

## 购买与试用

购买由 Apple 通过 StoreKit 处理，并与您的 App Store 账号关联。言续在设备上读取 Apple 提供的交易和权益记录，以确定购买权限和恢复购买。开发者不会通过 App 获取银行卡等支付信息。

符合条件的新订阅用户可通过 Apple 的购买界面开始 7 天免费试用。试用结束后，月度订阅会自动续订，除非用户提前在 Apple 账户中取消。另提供一次性终身购买。价格、资格、支付和续订由 Apple 管理。旧版本曾在设备钥匙串中保存免费用量计数；当前版本不再以该计数限制录音或收集，也不会将这些历史本地数据发送给开发者。

## 实时活动与快捷指令

言续使用 Apple 实时活动与快捷指令显示录音状态，并支持用户主动触发开始和停止录音。这些功能不会将录音内容传输给开发者。

## 外部服务与支持

开发者不会出售或出租您的 App 内容。用户主动发起的导出、文件提供商同步、购买和外部链接可能涉及 Apple 或其他服务；这些服务自身的信息处理适用各自的隐私规则。本政策不覆盖您选择配合导出文件使用的独立 Obsidian 插件或其他 App。

如果您主动发送支持邮件或提交 GitHub issue，您会将消息及附件提供给开发者和所使用的服务。开发者使用这些信息回复和处理您的请求。GitHub issue 是公开的。言续的支持邮箱链接不会自动附加录音或诊断资料。请勿发送私人录音、敏感的收集内容或与请求无关的信息。

## 联系方式

如有隐私或支持问题，请发送邮件至 [lufieu@gmail.com](mailto:lufieu@gmail.com)。不含敏感信息的问题也可以在以下地址提交：

https://github.com/lufie/KnowGrove-iOS-Support/issues

请勿在公开问题中附上私人录音或敏感的收集内容。
