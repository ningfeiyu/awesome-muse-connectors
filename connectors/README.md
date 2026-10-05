# Muse 连接器目录

本目录包含 150 个社区连接器技能，复制自 MIT 许可的 `muse-connectors` 项目，提交版本为 `6e31fd44a71f9f28377a1460e64cd7483c3cce22`，复制时间为 2026 年 9 月 24 日。源代码的版权和许可证保留在 [`LICENSE`](LICENSE) 中。这些技能由社区构建，未经 Meta 维护或验证。安装前请阅读每个技能，尤其是其 `Auth`、`Operating Rules`、`Files` 和 `Maturity` 部分。

## Meta 内置连接器

这些由 Meta 提供的集成与下文复制的社区技能相互独立。Meta 未发布完整的公开应用内目录，因此这是一份带日期的证据快照，而非完整列表或可用性保证。在依赖某项集成前，请查看 Muse 中的“连接器”界面。

| 连接器或分组 | 公开状态与已记录的范围 | 主要来源 |
|---|---|---|
| Facebook、Instagram、Threads | Meta 表示，当这些账户位于同一账户中心（Accounts Centre）时会自动连接。 | [Meta 帮助：连接器](https://www.meta.com/help/artificial-intelligence/1687253048996149/) |
| Apple Health、Android SMS | Meta 表示，这些的访问权限在设置完成后由设备设置管理。 | [Meta 帮助：连接器](https://www.meta.com/help/artificial-intelligence/1687253048996149/) |
| Gmail、Google Calendar、Outlook、Plaid、OpenTable、Google Docs、Spotify、Function Health、Withings、Tailscale、Peloton | 由 Meta 首席 AI 官在 2026 年 9 月 8 日发布时点名。该帖子未描述每个连接器的权限或操作。 | [Alexandr Wang 的发布帖](https://x.com/alexandr_wang/status/2097454574202495340) |
| Messenger | 在同一发布声明中被列为 Muse 专属连接器。 | [Alexandr Wang 的发布帖](https://x.com/alexandr_wang/status/2097454574202495340) |
| Ticketmaster | 现场活动发现和购票选项；购买在 Ticketmaster 上完成。 | [Ticketmaster 公告](https://business.ticketmaster.com/meta-and-ticketmaster-bring-live-event-discovery-to-muse/) |
| Duffel | 通过 Muse 搜索、预订、取消和管理航班行程；Duffel 在发布时宣布可用。 | [Duffel 公告](https://duffel.com/blog/millions-of-users-can-now-use-duffel-to-search-book-and-manage-holidays-on-muse-the-new-personal-ai-agent-from-meta) |
| HealthEx | 将个人健康记录连接到 Muse。 | [HealthEx 公告](https://www.healthex.io/press/healthex-muse-partnership) |
| Plaid 驱动的账户 | 用户连接的账户信息，用于财务指导和目标管理。 | [Plaid 公告](https://plaid.com/blog/meta-muse/) |
| Spotify | 搜索和播放音频、保存歌曲、创建播放列表以及安排播放。 | [Spotify 公告](https://newsroom.spotify.com/2026-09-23/spotify-meta-muse-agent/) |
| Shopify 商品目录；Walmart、Best Buy、American Eagle Outfitters、DICK’S Sporting Goods、Fanatics、Gap、Michael Kors、Sephora、Ulta 和 Wayfair | Meta 于 2026 年 9 月 23 日在 Connect 大会上宣布了这些购物连接。可用性和结账细节因合作伙伴而异。 | [Meta Connect 2026 公告](https://about.fb.com/br/news/2026/09/tudo-o-que-anunciamos-no-meta-connect-2026/) |
| Notion、Granola、GitHub、Box | Meta 于 2026 年 9 月 23 日在 Connect 大会上将其列为工作连接器。 | [Meta Connect 2026 公告](https://about.fb.com/br/news/2026/09/tudo-o-que-anunciamos-no-meta-connect-2026/) |
| Shop Pay、PayPal | Meta 于 2026 年 9 月 23 日在 Connect 大会上宣布其为额外的支付选项。 | [Meta Connect 2026 公告](https://about.fb.com/br/news/2026/09/tudo-o-que-anunciamos-no-meta-connect-2026/) |
| Expedia | Meta 宣布即将推出，用于行程规划。 | [Meta Connect 2026 公告](https://about.fb.com/br/news/2026/09/tudo-o-que-anunciamos-no-meta-connect-2026/) |
| Instacart | 已宣布为 Muse 杂货购物集成；请在 Muse 中查看推出状态。 | [Instacart 公告](https://company.instacart.com/updates/instacart-to-bring-personalized-grocery-shopping-to-muse-from-meta) |
| 1Password | Meta 称支持即将推出；应视为已宣布，而非已确认上线。 | [Meta：Muse](https://ai.meta.com/muse/) |

Meta 表示，许多连接器操作可以被限制为只读，发送电子邮件等重要操作默认需要批准，用户可以在设置中断开集成。用户创建的自定义连接器未经 Meta 审核；在启用之前，请参阅 [Meta 帮助：连接器](https://www.meta.com/help/artificial-intelligence/1687253048996149/) 以及服务提供商的隐私条款。

## 社区连接器技能

| 连接器 | 其技能文件中的摘要 |
|---|---|
| [airtable](./airtable/SKILL.md) | 列出 Airtable 数据库、读取表记录并添加记录。 |
| [alphavantage](./alphavantage/SKILL.md) | 股票报价和每日价格历史。只读。 |
| [amadeus](./amadeus/SKILL.md) | 使用 Amadeus 搜索旅行：航班报价和价格、机场自动补全、酒店报价、最低价日期。 |
| [anthropic](./anthropic/SKILL.md) | 检查你的 Anthropic API 访问权限并列出可用的 Claude 模型。只读。 |
| [apollo](./apollo/SKILL.md) | 搜索 B2B 联系人并丰富人员和公司信息。 |
| [aqara](./aqara/SKILL.md) | 通过 Aqara 开放云 API 读取设备属性并向 Aqara 设备发送控制命令：插座和墙壁开关、灯光（亮度、色温）、空调、受支持的门锁、窗帘电机以及已保存的场景，按住宅和房间组织。当用户询问或想要更改其 Aqara 设置中的任何内容时使用。Zigbee 设备需要 Aqara 网关在线。命令会驱动真实的物理硬件，因此写入操作需要确认门控（见 Operating Rules）。 |
| [asana](./asana/SKILL.md) | 查看分配给你的 Asana 任务并创建新任务。 |
| [ashby](./ashby/SKILL.md) | 搜索 Ashby 公共招聘板（无需密钥），并读写 Ashby ATS：候选人、职位、申请。 |
| [attio](./attio/SKILL.md) | 查询 CRM 记录、按匹配属性执行 upsert、添加备注和任务。 |
| [beatoven](./beatoven/SKILL.md) | Beatoven.ai 免版税音乐生成：创作曲目、轮询任务、下载音频、获取单独音轨。 |
| [beehiiv](./beehiiv/SKILL.md) | 列出出版物、订阅者和帖子；添加订阅者。 |
| [black-forest-labs](./black-forest-labs/SKILL.md) | Black Forest Labs FLUX 图像生成：flux-2-pro 和 flux-2-flex 文生图，支持异步轮询。 |
| [bluesky](./bluesky/SKILL.md) | 读取时间线、搜索帖子、发帖和关注。 |
| [brave-search](./brave-search/SKILL.md) | 来自 Brave 的独立网页搜索 |
| [buttondown](./buttondown/SKILL.md) | 读写 Buttondown：列出订阅者和邮件、添加订阅者、起草邮件。 |
| [buzzsprout](./buzzsprout/SKILL.md) | 管理 Buzzsprout 上的播客单集：列出和获取单集，创建、更新或删除单集，以及列出嵌入播放器。当用户希望在 Buzzsprout 托管的节目上发布或管理播客单集时使用。 |
| [calcom](./calcom/SKILL.md) | 列出预约和事件类型，创建预约。 |
| [calendly](./calendly/SKILL.md) | 读取和管理 Calendly：列出已安排的事件、事件类型、受邀者和可用时间表；取消预约。 |
| [canva](./canva/SKILL.md) | 通过 Canva Connect API 读取和管理 Canva 设计：列出设计和文件夹、查看设计详情、创建设计、上传素材以及导出设计。导出为异步任务：使用 export 提交，然后使用 export-status 轮询直至任务成功。 |
| [cartesia](./cartesia/SKILL.md) | 使用 Cartesia 从文本生成语音音频 |
| [clerk](./clerk/SKILL.md) | 列出、创建、更新和删除用户。 |
| [clickup](./clickup/SKILL.md) | 列出 ClickUp 工作区和任务，并创建任务。 |
| [cloudflare](./cloudflare/SKILL.md) | 列出你的 Cloudflare 区域并读取 DNS 记录。只读。 |
| [cloudinary](./cloudinary/SKILL.md) | 通过 Upload 和 Admin API 管理 Cloudinary 上的媒体：上传图片和视频、列出和查看素材、更新元数据和标签、删除素材，以及检查套餐用量（额度、存储、带宽、转换）。 |
| [coda](./coda/SKILL.md) | 列出文档、读取表和行、添加行。把你的文档当作数据库。 |
| [deepgram](./deepgram/SKILL.md) | 使用 Deepgram 将预录音频文件转写为文本（可选说话人分离、摘要、主题、情感分析），并合成语音 |
| [deepl](./deepl/SKILL.md) | 在 30 多种语言之间翻译文本，检查用量。 |
| [deepseek](./deepseek/SKILL.md) | 与 DeepSeek 对话 |
| [descript](./descript/SKILL.md) | 使用 Descript 工作 |
| [devto](./devto/SKILL.md) | 读写 dev.to：个人资料、个人文章（已发布、草稿、全部）、按用户名读取公共文章，以安全的草稿默认值创建和更新文章。 |
| [digitalocean](./digitalocean/SKILL.md) | 列出你的 DigitalOcean Droplet 和域名。只读。 |
| [discord](./discord/SKILL.md) | 读取服务器和频道，发送消息和私信。 |
| [docusign](./docusign/SKILL.md) | 起草并发送签名信封（默认演示环境）、检查信封状态，以及下载已签署的文件。 |
| [dub](./dub/SKILL.md) | 创建短链接、读取分析数据、跟踪转化。 |
| [ecovacs](./ecovacs/SKILL.md) | 通过科沃斯官方开放平台控制 Ecovacs DEEBOT 扫地机器人：列出已绑定的机器人、读取机器人状态和电量、开始/暂停/恢复/停止清扫、让机器人返回基站，以及设置扫/拖工作模式。当用户提到其 DEEBOT 或扫地机器人时使用。 |
| [elai](./elai/SKILL.md) | 使用 Elai 构建 AI 数字人演讲视频：列出可用的数字人、查看视频及其渲染状态、提交渲染任务，并轮询直至渲染完成。当用户希望根据脚本或幻灯片生成口播视频时使用。 |
| [elevenlabs](./elevenlabs/SKILL.md) | 检查 ElevenLabs 订阅用量、列出声音，并生成文字转语音音频（TTS 需要 --confirm，会消耗字符数）。 |
| [etsy](./etsy/SKILL.md) | 读取 Etsy 店铺数据：收据、商品列表、交易、付款账本；创建商品列表。 |
| [exa](./exa/SKILL.md) | 带页面正文的神经网页搜索：一次调用返回带摘要的排名来源。只读。 |
| [fal-ai](./fal-ai/SKILL.md) | 使用 fal.ai 生成媒体：图像、视频、音频、音乐，共用一个密钥。向数百个模型提交任务、轮询状态、获取结果、上传文件。 |
| [figma](./figma/SKILL.md) | 查询你的 Figma 用户、读取文件元数据，并在文件上发表评论。 |
| [firecrawl](./firecrawl/SKILL.md) | 抓取页面、爬取站点、搜索网页。 |
| [flyio](./flyio/SKILL.md) | 列出应用和机器，管理机器生命周期。 |
| [framer](./framer/SKILL.md) | 验证 Framer 项目 |
| [front](./front/SKILL.md) | 读取你的 Front 共享收件箱，并在会话中回复、分配队友和添加标签（写入需要 --confirm）。 |
| [gemini](./gemini/SKILL.md) | Google Gemini 媒体生成：Nano Banana 图像、Imagen 4 图像、Veo 视频、TTS、模型列表。 |
| [github](./github/SKILL.md) | 查看你的个人资料、列出仓库、列出未关闭的 issue，并创建 issue。 |
| [gitlab](./gitlab/SKILL.md) | 你的 GitLab 用户、项目、未关闭的合并请求，以及 issue 创建。 |
| [google-nest](./google-nest/SKILL.md) | 通过 Smart Device Management (SDM) API 读取 Google Nest 设备的特征并执行命令：恒温器（模式、设定值、环境读数）、摄像头和门铃（事件、直播流生成）。当用户询问其 Nest 恒温器、想要更改制热/制冷，或想要摄像头/门铃状态时使用。恒温器命令会启动或停止真实的暖通空调设备，因此需要确认门控（见 Operating Rules）。 |
| [gumroad](./gumroad/SKILL.md) | 查看你的 Gumroad 产品和销售。设计上只读。 |
| [heygen](./heygen/SKILL.md) | HeyGen 数字人和口播视频：提示词生成视频代理、多场景数字人视频、状态轮询、数字人和声音列表。 |
| [home-assistant](./home-assistant/SKILL.md) | 读取你的 Home Assistant 实例上的实体状态并调用服务。服务调用会先确认。 |
| [homey](./homey/SKILL.md) | 通过 Homey Web API 在 Homey Pro（本地）或 Homey 云账户上读取设备状态并写入能力值：灯光和插座、调光器和颜色、恒温器、联网门锁、百叶窗和窗帘，以及列出 Flow（自动化）。当用户询问或想要更改与其 Homey 配对的任何设备时使用。写入会驱动真实的物理硬件，因此需要确认门控（见 Operating Rules）。 |
| [hubitat](./hubitat/SKILL.md) | 通过官方 Maker API 应用读取 Hubitat Elevation 中枢上的设备状态并调用能力命令：灯光和调光器、插销锁、车库门控制器、恒温器、位置模式，以及 Hubitat Safety Monitor (HSM)。当用户询问或想要更改与其 Hubitat 中枢配对的任何设备时使用。命令会驱动真实的物理硬件，因此写入需要确认门控（见 Operating Rules）。 |
| [hubspot](./hubspot/SKILL.md) | 在你的 HubSpot CRM 中列出和搜索联系人、创建联系人，以及列出交易。 |
| [huggingface](./huggingface/SKILL.md) | 验证你的 Hugging Face 账户并搜索模型中心。只读。 |
| [hume-ai](./hume-ai/SKILL.md) | 使用 Hume 合成语音 |
| [ideogram](./ideogram/SKILL.md) | Ideogram 文生图，拥有本目录中最强的文字渲染能力：生成、编辑、重混、放大、描述、平衡。 |
| [kit](./kit/SKILL.md) | 读写 Kit（ConvertKit）：列出订阅者、广播、序列、标签；起草广播。 |
| [kling](./kling/SKILL.md) | Kling AI 视频生成，使用客户端 JWT 认证：文生视频、图生视频、状态轮询、片段延长、唇形同步。 |
| [langfuse](./langfuse/SKILL.md) | 查询追踪和观测数据，管理提示词和评分。 |
| [leaf-agriculture](./leaf-agriculture/SKILL.md) | 通过 Leaf Agriculture 读取和管理农场数据。Leaf Agriculture 是一个统一的农场数据 API，以自助访问方式聚合了需要合作伙伴授权的 OEM 平台：John Deere、CNH Industrial（Case IH/New Holland）、Climate FieldView、Trimble、Raven 和 AgLeader。它暴露的原语（田地、边界、种植/收获/施药/耕作的机器作业文件，以及实际灌溉数据）正是以农户为先的金融科技和供应链数字化产品所需要的。这是无需合作伙伴协议即可访问需要合作伙伴授权的 OEM 数据的实用途径：单个提供商连接需要该种植户 |
| [lemon-squeezy](./lemon-squeezy/SKILL.md) | 读取 Lemon Squeezy 收入：列出订单、订阅、客户、产品；创建结账链接。 |
| [letta](./letta/SKILL.md) | 使用 Letta 代理记忆：列出代理、读取核心记忆块、列出或添加归档段落、创建记忆块、向代理发送消息以记录记忆。 |
| [linear](./linear/SKILL.md) | 通过 Linear 查看分配给你的 issue 并创建 issue |
| [lob](./lob/SKILL.md) | 通过 Lob 发送实体邮件 |
| [loops](./loops/SKILL.md) | 管理邮件联系人、触发循环、发送事务性邮件。 |
| [luma](./luma/SKILL.md) | Luma Dream Machine 视频生成：文生视频和图生视频、状态轮询、取消、图像上传。 |
| [mastodon](./mastodon/SKILL.md) | 读写 Mastodon：验证账户、列出自己的帖子和关注者、发布嘟文（支持原生定时发布）、上传媒体。 |
| [mem0](./mem0/SKILL.md) | Mem0 记忆 CLI：从消息添加记忆、语义搜索、读取或删除记忆、轮询异步事件。 |
| [mercury](./mercury/SKILL.md) | 查看 Mercury 银行账户和交易。设计上只读。 |
| [mistral](./mistral/SKILL.md) | Mistral AI |
| [monday](./monday/SKILL.md) | 列出看板、读取条目、创建条目。基于 GraphQL 的项目管理。 |
| [moonraker](./moonraker/SKILL.md) | 通过 Moonraker API 服务器（Mainsail、Fluidd 和 RatOS 背后的后端）控制基于 Klipper 的 3D 打印机：读取服务器和打印状态、列出和上传 gcode 文件、开始/暂停/恢复/取消打印、触发紧急停止、切换智能插座设备，以及（门控）运行原始 G-code。当用户提到 Moonraker、Klipper、Mainsail 或 Fluidd 时使用。 |
| [n8n](./n8n/SKILL.md) | 列出和管理工作流，读取执行记录。 |
| [neon](./neon/SKILL.md) | 检查 Neon 无服务器 Postgres 项目、分支和数据库。分支的创建和删除需要精确匹配确认；连接密码会被掩码处理。 |
| [netlify](./netlify/SKILL.md) | 列出你的 Netlify 站点和最近的部署。只读。 |
| [newsapi](./newsapi/SKILL.md) | 头条新闻和全文新闻搜索。只读。 |
| [notion](./notion/SKILL.md) | 搜索和查询 Notion，以及创建页面、追加块和更新页面属性（写入需要 --confirm）。 |
| [octoprint](./octoprint/SKILL.md) | 通过本地 REST API 控制 OctoPrint 3D 打印机：读取打印机状态和温度、监控打印进度、开始/暂停/取消/重启任务、上传和选择 gcode 文件、设置热端和热床温度、点动或回零各轴，以及（门控）运行原始 G-code。当用户提到其 OctoPrint 实例或由其驱动的打印机时使用。 |
| [openai](./openai/SKILL.md) | 检查你的 OpenAI API 访问权限并列出你的密钥可用的模型。只读。 |
| [openrouter](./openrouter/SKILL.md) | 浏览带每 token 定价的模型目录；检查你的密钥用量。只读。 |
| [openweathermap](./openweathermap/SKILL.md) | 任何城市的当前天气和 5 天预报。只读。 |
| [opusclip](./opusclip/SKILL.md) | 使用 OpusClip 将长视频转换为带字幕的竖屏短片段 |
| [oura](./oura/SKILL.md) | 读取 Oura Ring 健康数据：睡眠评分、睡眠会话、准备度、锻炼和血氧（SpO2）。 |
| [paddle](./paddle/SKILL.md) | 查看 Paddle 交易和客户。设计上只读。 |
| [patreon](./patreon/SKILL.md) | 读取 Patreon 活动、会员、档位和身份信息（只读）。 |
| [perplexity](./perplexity/SKILL.md) | 带引用地提问，搜索网页。 |
| [pexels](./pexels/SKILL.md) | 搜索 Pexels |
| [philips-hue](./philips-hue/SKILL.md) | 本地控制 Philips Hue 灯光：列出灯光和房间、设置亮度/颜色、激活场景、读取传感器。 |
| [pipedrive](./pipedrive/SKILL.md) | 列出交易和联系人，创建交易。为你的销售管道服务的 CRM。 |
| [plain](./plain/SKILL.md) | 查找客户，管理支持会话。 |
| [playht](./playht/SKILL.md) | 使用 PlayHT 声音从文本生成语音音频，浏览库存和克隆声音，并创建即时声音克隆。当用户需要旁白或配音、声音库查询，或从样本克隆声音时使用。 |
| [podbean](./podbean/SKILL.md) | 管理 Podbean 上的播客托管：列出播客及其单集，创建、更新或删除单集。Podbean |
| [polar](./polar/SKILL.md) | 读取 Polar 订单、订阅、产品和客户；创建结账和退款。 |
| [polymarket](./polymarket/SKILL.md) | 只读的预测市场数据：事件、市场、价格、订单簿。无交易功能，无需 API 密钥。 |
| [posthog](./posthog/SKILL.md) | 你的 PostHog 用户、项目和已保存的洞察。只读。 |
| [postmark](./postmark/SKILL.md) | 发送事务性邮件，检查投递和退信情况。 |
| [printful](./printful/SKILL.md) | 读取 Printful 产品和订单，创建订单和效果图。 |
| [prusa-connect](./prusa-connect/SKILL.md) | 通过官方 Prusa Connect 云 API 读取 Prusa 3D 打印机状态：列出打印机及其状态、列出任务和文件、查看摄像头、读取打印统计信息，以及将 gcode 文件上传到打印机存储。当用户提到 Prusa Connect 或联网的 Prusa 打印机（MK3/MK4/CORE One）时使用。 |
| [rachio](./rachio/SKILL.md) | 通过公共 Rachio API 控制 Rachio 智能灌溉控制器。检查当前登录用户、查看控制器正在运行的内容、让特定分区浇水指定的秒数，以及在紧急情况下关闭所有水源。当用户询问洒水器、浇水计划或灌溉分区时使用。 |
| [railway](./railway/SKILL.md) | 列出项目和部署，设置变量，重新部署。 |
| [ramp](./ramp/SKILL.md) | 企业支出的只读视图：交易、卡片和限额、用户、部门。设计上不支持任何支出操作。 |
| [readwise](./readwise/SKILL.md) | 搜索你的高亮和书籍，保存新的高亮。 |
| [remove-bg](./remove-bg/SKILL.md) | 使用 remove.bg API 移除图像背景：提交本地文件或图像 URL，获得保存到本地路径的透明 PNG。还可以检查账户 |
| [render](./render/SKILL.md) | 列出你的 Render 服务和最近的部署。只读。 |
| [replicate](./replicate/SKILL.md) | 运行 AI 模型，轮询预测结果。 |
| [resend](./resend/SKILL.md) | 通过 Resend 发送邮件并检查投递状态。每次发送都会先与你确认。 |
| [restream](./restream/SKILL.md) | 管理 Restream 多平台直播：读取你的个人资料、列出直播目标（频道）、切换目标或编辑频道元数据，以及获取你的推流密钥。当用户希望在不打开 Restream 控制面板的情况下控制直播流的去向时使用。 |
| [runway](./runway/SKILL.md) | Runway 开发者 API：文生视频、图生视频、任务轮询、视频放大、唇形同步。 |
| [sendgrid](./sendgrid/SKILL.md) | 发送邮件，检查统计信息和个人资料。 |
| [sentry](./sentry/SKILL.md) | 列出组织和项目，分诊过去 24 小时内未解决的问题，并解决/归档/分配问题。 |
| [shippo](./shippo/SKILL.md) | 通过一个 API 使用多家承运商（USPS、UPS、FedEx、DHL 等）发货：获取货件报价；购买可打印的邮资标签；跟踪包裹；退还未使用的标签。当用户需要为包裹询价或购买运输服务时使用。 |
| [shopify](./shopify/SKILL.md) | 查看订单、产品、客户；经确认后创建产品和折扣。永远不写入订单或客户数据。 |
| [slack](./slack/SKILL.md) | 读取频道、发布消息、列出用户。需求最高的工作场所连接器。 |
| [smartcar](./smartcar/SKILL.md) | 通过一个标准化 API 读取和控制多个品牌（Tesla、Ford、GM、Toyota、BMW、Hyundai 等）的联网汽车。读取里程表、位置、电量和电池水平、燃油量和胎压；锁车/解锁车门；开始/停止充电；设置充电限额和计划；控制内置导航。当用户提到其汽车且该品牌在此没有专用连接器，或需要跨品牌车辆遥测和控制时使用。 |
| [smartthings](./smartthings/SKILL.md) | 在 Samsung SmartThings 账户中读取设备状态并发出能力命令：位置、设备、开关、调光器、门锁、恒温器、警报器、车库门控制器和窗帘。当用户询问或想要更改与其 SmartThings 中枢或云账户配对的任何设备的状态时使用。此连接器驱动真实的物理硬件，因此每次写入都需要确认门控（见 Operating Rules）。 |
| [spotify](./spotify/SKILL.md) | 读取你的个人资料、播放列表、热门曲目和艺人，并搜索目录。播放列表和媒体库的写入需要你的确认。 |
| [square](./square/SKILL.md) | 使用 Square 卖家账户：列出位置和付款、创建订单、将结账推送到实体 Square Terminal 进行面对面支付、直接对支付来源扣款、取消待处理的 Terminal 结账，以及退款。当用户需要通过 Square 收款或退款时使用。 |
| [stripe](./stripe/SKILL.md) | Stripe 只读可见性：余额、近期扣款、客户。不附带任何写入命令：扩展到写入是有意推迟到 v2 的。 |
| [supabase](./supabase/SKILL.md) | 在你的 Supabase Postgres 数据库中列出表、查询行，以及插入/更新/删除行。 |
| [supermemory](./supermemory/SKILL.md) | 使用 Supermemory 存储和召回：添加记忆和文档、混合搜索、上传文件、调整设置。 |
| [switchbot](./switchbot/SKILL.md) | 通过官方 OpenAPI v1.1 读取 SwitchBot 设备状态并发送命令：SwitchBot Bot（物理按钮按压器）、SwitchBot Lock、Curtain 和 Blind Tilt 电机、插座、灯光、空调、红外遥控器，以及已保存的场景。当用户询问或想要更改其 SwitchBot 设置中的任何内容时使用。命令会驱动真实的物理硬件，因此写入需要确认门控（见 Operating Rules）。 |
| [tally](./tally/SKILL.md) | 列出表单、读取提交内容、管理表单块。 |
| [tavily](./tavily/SKILL.md) | 快速、干净的网页研究：一次调用返回 AI 答案以及带摘要的排名来源。只读。 |
| [telegram](./telegram/SKILL.md) | 通过你自己的 Telegram 机器人发送消息并读取更新。机器人可以 |
| [tesla-fleet-api](./tesla-fleet-api/SKILL.md) | 通过官方 Tesla Fleet API 控制 Tesla 车辆：读取实时车辆状态、唤醒休眠中的车辆，并发送签名命令（锁车/解锁、无钥匙驾驶、充电控制、预调节、鸣笛/闪灯、后备箱、哨兵/代客模式、限速、导航）。当用户提到其 Tesla 汽车或请求车辆操控时使用。 |
| [tesla-powerwall](./tesla-powerwall/SKILL.md) | 通过官方 Tesla Fleet API 监控和控制 Tesla 能源站点（Powerwall、太阳能）。读取实时功率流、电池状态和站点设置；更改备用储备百分比、运行模式和 Storm Watch（风暴监视）。当用户提到其 Powerwall、Tesla 能源站点、备用储备或风暴模式时使用。 |
| [ticktick](./ticktick/SKILL.md) | 读写 TickTick：列出项目和任务、创建任务、完成和删除任务。 |
| [tiktok](./tiktok/SKILL.md) | 读取你的 TikTok 个人资料和视频列表。API 访问需要先获得 TikTok 应用批准，且未提供发帖功能。 |
| [todoist](./todoist/SKILL.md) | 在 Todoist 中列出任务、创建任务并将其标记为完成。 |
| [transistor](./transistor/SKILL.md) | 管理 Transistor.fm 上的播客托管：列出节目和单集、创建单集草稿、更新或删除单集，以及通过 Transistor 上传单集音频 |
| [triggerdev](./triggerdev/SKILL.md) | 触发后台任务、列出运行记录、管理调度。 |
| [tuya](./tuya/SKILL.md) | 读取 Tuya Cloud / Smart Life 设备的状态并发送控制命令：智能插座和开关、灯光、恒温器、窗帘电机和受支持的智能门锁，以及执行已保存的场景。当用户询问或想要更改通过 Tuya 或 Smart Life 应用配对的任何设备时使用。命令会驱动真实的物理硬件，因此写入需要确认门控（见 Operating Rules）。 |
| [twitch](./twitch/SKILL.md) | 通过 Helix API 读写 Twitch：频道资料、关注者统计、直播状态、过往视频、频道标题和游戏更新、剪辑创建。 |
| [typeform](./typeform/SKILL.md) | 列出表单和回复、创建表单，并经确认后管理回复 webhook。 |
| [uber-direct](./uber-direct/SKILL.md) | 通过 Uber Direct 为食品、零售、杂货或包裹配送调度当日达骑手。在不调度任何人的情况下获取价格和时间报价，在用户批准后创建配送、检查其状态，并取消待处理的配送。当用户需要在本地当天取送物品时使用。 |
| [unifi-protect](./unifi-protect/SKILL.md) | 通过官方 Integration API 从本地 UniFi Protect 控制台（Protect 5.3+）读取摄像头状态和静态快照，并调整摄像头设置：PTZ 位置、泛光灯、提示音、对讲。当用户询问其 UniFi 摄像头看到了什么、想要保存快照，或想要更改摄像头行为时使用。一切都在本地控制台上运行，不依赖云端。 |
| [unsplash](./unsplash/SKILL.md) | 搜索 Unsplash |
| [upstash](./upstash/SKILL.md) | 通过 REST 运行 Redis 命令。 |
| [vapi](./vapi/SKILL.md) | 管理语音 AI 助手、电话号码和通话。外呼需要精确匹配确认；默认使用测试号码。 |
| [veed](./veed/SKILL.md) | 使用 VEED 移除视频背景 |
| [vercel](./vercel/SKILL.md) | 查看你的 Vercel 账户、项目和最近的部署。 |
| [webflow](./webflow/SKILL.md) | 使用 Webflow Data API v2：列出站点、查看站点详情、浏览 CMS 集合和条目、创建/更新/删除 CMS 条目，以及发布站点。使用来自站点设置的每站点令牌。 |
| [wise](./wise/SKILL.md) | 查看 Wise 资料和多币种余额。设计上只读。 |
| [x](./x/SKILL.md) | 发帖、搜索、点赞、私信。注意：没有可用的免费读取层级。 |
| [xai](./xai/SKILL.md) | 通过 xAI 查询 Grok 聊天补全并列出可用的 Grok 模型 |
| [ynab](./ynab/SKILL.md) | 读写 YNAB 预算：列出预算、账户、余额、交易和分类；记录交易。 |
| [youtube](./youtube/SKILL.md) | 读取频道和视频、搜索，以及经确认后上传和评论。 |
| [zep](./zep/SKILL.md) | 使用 Zep 工作 |

## 提交连接器

提交一个拉取请求（pull request），添加一个自包含的文件夹，其中包含 `SKILL.md` 以及仅在其 `## Files` 清单中列出的文件。请附上 API 的公开来源、准确说明认证范围和允许的主机、对重要写入操作要求批准，并在实际测试通过之前将连接器标记为 `Draft`。切勿提交凭据。审核清单请参见 [CONTRIBUTING.md](../CONTRIBUTING.md)。
