# Clash，小火箭节点 机场推荐与机场评测
🔘1.	什么是机场？	

VPN，即虚拟专用网络，本质上是一种代理工具，最早用于在公司或学校外部连接其内部网络，并不特指翻墙代理。随着需求变化，VPN逐渐被广泛用于跨区域访问内容，因此现在市场上推荐的Express VPN、Nord VPN等产品多是以翻墙为主，但广告铺天盖地，并不推荐使用。

“机场”是后期专为翻墙需求而出现的服务，通常通过购买大量VPS线路，搭建SS、SSR、Vmess等协议供用户使用。机场服务通常需要配合代理软件，如Clash、小火箭、v2rayN、QuantumultX等进行使用，也有部分机场提供一键客户端，多数是基于Clash的套壳软件。

🔘2.	为什么机场都差不多？怎么挑选？

大多数机场都是使用开源免费的V2board或SSpanel搭建的，因此前端界面看起来都很相似，这也是常见的情况。搭建过程相对简单，而少数页面风格有所不同的机场，通常是因为购买了付费主题。
4.	在跨境网络优化中，常见的技术概念包括专线、中转、隧道、BGP、前置等，它们在提升网络稳定性和速度方面各有优势。

专线：专线是一条从A点到B点的专用网络连接，比如深圳到香港的深港专线，这种线路不会经过公网，因此延迟低、网络环境稳定。常见的专线方案有IEPL（国际以太网专线）和IPLC（国际私有租用线路）。IPLC是真正的点对点专线，而IEPL支持多端连接，通常用于跨国企业连接多个站点。一般机场购买的是IEPL，相比IPLC更便宜，但对翻墙需求已足够。专线贵，但效果不稳定时体验反而不如普通中转。

隧道：隧道技术是通过购买一个国内服务器作为入口，再加一台境外服务器用于流量转发。例如，广东移动作为入口，通过TLS加密流量传输到香港的CMI服务器后解密，然后发送到目的地服务器。这种方式的优势在于提供了一层加密保障，可以有效绕过部分封锁，提升稳定性，但仍属于公网中转的一种。

中转：中转是指利用一个（通常在国内）服务器将流量转发到最终的境外落地服务器。中转服务器一般经过出境优化，能选用速度更快、抗封锁能力更强的线路，比如电信用户可以通过广东移动的中转实现更快速的出境速度。相较于直连，中转方式可以避免IP和端口被轻易封禁，同时可以优化线路速度，尤其对电信用户改善明显。机场为了抗封锁，通常还会将国内中转服务器和隧道技术结合使用。

BGP：BGP（边界网关协议）是一种路由协议，用于在不同自治系统之间选择最优路径。例如，电信和联通之间访问速度通常较慢，但若服务器采用BGP线路，无论用户使用的是电信、联通还是其他运营商，访问速度都会得到优化。BGP通过控制路由传播，确保用户访问服务器时获得最佳路径。

前置：前置指的是在中转入口之前再添加一台国内机器作为入口，目的是防止政府通报封禁。前置技术通过增加一层入口，减少通报后被机房封锁的风险。

转发：一些小型机场由于无法承受单独购置中转服务器的高成本，可能会选择和他人共享转发服务。这样，机场通过转发将用户流量转发到更高质量的中转服务器上。

关于带宽和线路质量，通常机场的用户体验与机场购买的带宽总量和线路质量密切相关。比如，如果一个机场带宽不足，即使采用专线，用户体验也可能受限。而流媒体解锁方面，机场一般通过购买DNS解锁服务，确保用户能正常观看区域受限的内容，如Netflix等。

总结：相同带宽条件下的线路质量排序为：IEPL专线中转 > 隧道中转 > 优化的公网中转（如广东移动、湖南联通） > 普通直连。在满足观看视频流畅的前提下，机场最重要的还是带宽、稳定性和资源质量，而稳定性往往依赖机场主上游的线路质量和维护能力。

🌟机场推荐🌟

1.	🪐M78星云🚀（7.8元起）

🔴最高2000Mbps的速率，晚高峰速度出色。

🔴附带Emby服务，数万部国内外4K电影，电视剧免费观看。

🔴奈飞，迪士尼，ChatGPT等服务全解锁。

🔴最低7.8元起，价格亲民，购买高级套餐赠送Netflix或者Disney+独立位。

🔴提供一键客户端，使用无门槛。

🔴不限制设备数量（禁止与陌生人共享账号）

🔴无网速限制

🔴新用户7.8折优惠码：m78-22off

⚪️M78星云机场是高品质中转和专线机场的代表，凭借高达3000Mbps的极速，尤其在晚高峰时段依旧保持卓越的速度表现，为用户带来无缝的网络体验。附带的Emby服务更是亮点，数万部国内外4K电影和电视剧尽在其中，供用户免费观看。平台支持全解锁奈飞、迪士尼、ChatGPT等热门服务，体验全面无阻。价格亲民，起步仅需7.8元，升级至高级套餐还赠送Netflix或Disney+独立位，让娱乐体验更上一层楼。便捷的一键客户端设计，使用无门槛，适合各类用户。M78星云机场是追求品质与性价比用户的不二之选！

⚫️官网地址1：[m78star.cloud](https://m78.at/#/register?code=ygqbIMQ1) (智能分流）

⚫️官网地址2：[m78.pro](https://www.m78.pro/#/register?code=ygqbIMQ1) （国内可以直接打开）

⚫️发布页：[m78星云.com](https://m78星云.com)

～🪐M78星云🚀 机场概况～

🔘开业时间：2023年，老板在境外运营。

🔘节点信息：提供香港，新加坡，日本，台湾，美国等热门地区外，还包括了多达20+个稀有地区节点，包括韩国、阿根廷、土耳其、南极、乌克兰、印度尼西亚、丹麦、德国、荷兰、埃及、尼日利亚、俄罗斯、泰国、越南，菲律宾，马来西亚，澳门等，地区还在不断增加中。

🔘速度：下图为晚高峰时的Speedtest测速结果。值得注意的是，即使是在周末的晚上9点，宽带速度仍然非常出色，达到了750+Mbps的恐怖速度。使用中国电信1000Mbps家宽测试。（机场的晚高峰时间为晚上七点到凌晨一点）在YouTube方面，M78星云的速度同样非常出色，达到了惊人的31万。这个速度是在周末晚高峰时段测试得到的。可以流畅地观看高清的4K 60帧视频，随意拖动也完全没有卡顿的问题。

🔘限制：不限制设备数量：用户可以在多个设备上同时使用M78星云，无需担心设备数量的限制。（禁止与陌生人共享账号）

🔘解锁服务：支持解锁ChatGPT/OpenAI，该机场在流媒体解锁方面表现非常出色，可以解锁包括但不限于Netflix、Disney+、ChatGPT、DMM、DAZN、HBO等在内的各种流媒体平台。几乎所有节点都能够解锁市面上常见的流媒体，甚至包括对高要求的奈飞自制剧的解锁。

🔘其他信息：仅限中国大陆使用（新疆不可用），提供Windows、Mac、安卓的一键客户端

🔘Emby介绍

![图片 1](https://github.com/user-attachments/assets/64828087-fcd0-4d4a-823f-6b16f8255743)

网站了解：https://qimiao.xyz/archives/1709468441733

💰价格💰

⭕️7.8元 80G/月

⭕️12.8元 150G/月

⭕️22.8元 300G/月（最推荐）

🌹35元 500G/月 季付送Disney+会员（独立位）

🌹49元 650G/月 季付送Netflix会员（独立位）

─────────────────────────────────────────────────────────────

2.	ℹ️BoostNet(39/月200G)

🔴Shadowsocks 专用协议

🔴IEPL 专线机场

🔴不错的流媒体解锁

🔴新用户 8 折福利

⚪️Boost Net 是一家专线实力强、相对小众的精品机场，采用Shadowsocks协议，提供公网隧道中转和IEPL专线节点，常用节点为1倍率，冷门节点设为高倍率。其节点支持解锁Netflix、Disney+、TikTok和ChatGPT。主打广港、深港双IEPL内网专线，速度快、延迟低且稳定。适合对速度和体验有高要求的用户。新人可享8折优惠，优惠码为：boost。

⚫️[Boost 官网地址](https://boostnet1.com/register?code=cGSFoQhL) 


ℹ️Boost Net 机场概况

🔘开业时间：2024年，老板在墙外运营。

🔘线路入口及过境：采用广东入口，通过IEPL专线中转。

🔘节点信息：提供30+节点，覆盖香港、台湾、新加坡、日本、美国、英国、马来西亚、土耳其、阿根廷等地区。

🔘协议及支持：使用Shadowsocks协议（不支持SSR软件），支持UDP协议。

🔘限制：软性限制最多5个IP同时登录。

🔘解锁服务：支持解锁ChatGPT/OpenAI，基本支持Netflix和Disney+。

🔘屏蔽：屏蔽部分墙外新闻网站（如轮媒、RFA、品葱）及SSH 22端口。禁止使用SMTP、POP3、IMAP协议（邮箱官方APP和网页访问不受影响）。

🔘IPv6支持：部分香港、台湾、日本、美国节点支持IPv6。

🔘支付方式：支持支付宝和微信支付。

🔘客服及订阅：提供客服服务，采用v2board面板，节点订阅位于首页仪表盘的【一键订阅】按钮。

🔘其他信息：无TG频道，套餐价格不含手续费（额外6-9%），仅限中国大陆使用（新疆不可用），提供Windows和Mac的一键客户端，未提供家用宽带方案。

💰套餐(所有套餐节点一样):💰

流量	价格

⭕️10G/月	10/月

⭕️200G/月	39/月;100/季;220/半年;350/年

⭕️400G/月	58/月;150/季;310/半年;500/年

⭕️1000G/月	108/月;280/季;600/半年;1000/年

⭕️3000G/月	500/月;1500/季;2888/半年;5688/年

─────────────────────────────────────────────────────────────

3.	🐰悠兔(120/年/200G)
   
🔴Shadowsocks 机场

🔴IPLC专线翻墙机场

⚪️机场采用IEPL专线结合隧道中转，提供大带宽过境，具备稳定性和速度优势，适合偏好低调、少人使用的用户，且不追求大量节点。后端设计为多入口+负载均衡，多种落地配置，确保单个入口故障不会影响整体服务，同时提供按量付费作为备用选择。用户体验良好，老板服务周到，新用户可使用8折优惠码“888”。

⚫️[悠兔 官网地址](https://link1.youtu6.shop/register?aff=yyiNo3Ot) 

🐰机场概况

🔘开业时间：2022年，老板位于墙外。

🔘线路：入口位于广东，采用IEPL专线+隧道公网中转，35+节点，后端负载均衡，多个落地服务器。

🔘协议及支持：使用Shadowsocks协议，支持UDP，软性限制同时登录5个IP。

🔘解锁与屏蔽：支持ChatGPT/OpenAI解锁，部分墙外新闻网站（如轮媒、RFA、品葱）和SSH 22端口被屏蔽；传统邮件协议（SMTP/POP3/IMAP）禁止，但不影响邮箱APP和网页使用。

🔘节点分布：覆盖澳洲、香港、台湾、新加坡、日本、美国、英国、印度、马来西亚、阿根廷、土耳其等地区。

🔘落地资源：包括Akari、Tanaka、PoloCloud、DigitalOcean、nexeon、Eons、Ipxo LLC、英国家宽、香港HGC、台湾家宽Hinet、日本软银等。

🔘支付方式：支持支付宝和微信支付，套餐价格不含手续费（手续费为6-9%）。

🔘适用范围：限中国大陆使用，不适用于国外用户，新疆地区不可使用。

🔘推荐用户：适合稳定、无特殊需求的用户。

🔘客户端：提供iOS、Windows、Mac、安卓的一键客户端。

🔘家用宽带：部分节点为英国和日本的原生家宽。

🔘流量重置：提前用完流量需在首页点击【重置】付费重置；订阅也在首页。

💰套餐(所有套餐节点一样)💰

流量	价格

⭕️50G/月	55/季;110/半年;200/年

⭕️150G/月	29/月;85/季;160/半年;300/年

⭕️300G/月	39/月;110/季;210/半年;400/年

⭕️500G/月	59/月;160/季;310/半年;500/年

⭕️1000G/月	100/月;280/季;520/半年;1000/年

按量付费：一年120总共200G。可以做备用。

─────────────────────────────────────────────────────────────

4.	WgetCloud(59/月140G)
   
🔴2024 稳定翻墙机场推荐

🔴Trojan 协议机场

🔴高端专线翻墙机场

🔴新用户注册8折优惠

⚪️机场采用多入口专线+中转配置，具备大量带宽冗余，稳定性高。由香港老板运营，拥有多年机场行业经验，配备自有机房和自研面板。节点分为B、C、H三个组，分别对应运营商BGP路由、AWS骨干网，以及更高优先级的C组，各组用户数不同，精品组用户较少，负载更低。通过指定链接注册的新用户可享8折优惠，仅限一次使用。

⚫️ [WgetCloud 官网地址](https://invite.wgetcloud.ltd/auth/register?code=LIXK1C) 

GaCloud 机场概况

🔘开业时间：2021年，老板位于香港。

🔘线路配置：广州入口，过境采用IEPL内网，59个落地IP，支持Shadowsocks（路由器）和Trojan协议（以Trojan为主），支持UDP。

🔘用户限制：最多支持3台客户端同时使用。

解锁与屏蔽：部分ChatGPT解锁（台湾3动态IP支持，但不保证可用）；屏蔽部分墙外新闻网站（轮媒、VOA、RFA、品葱），SSH 22端口屏蔽。

🔘节点分布：覆盖香港、日本、新加坡、美国、台湾、加拿大、俄罗斯、韩国、印尼、印度、土耳其、巴西、德国、泰国、澳洲、英国、荷兰、菲律宾、马来西亚。

🔘落地服务商：Hinet、Linode、Misaka、EZN-ECN。

🔘通知与支持：无TG频道，主要通过邮件通知；提供一键客户端和专属客服服务。

🔘支付方式：仅支持支付宝支付，需充值后购买套餐，包含手续费。

🔘适用范围：仅限中国大陆内使用，不适用于大陆外用户。

🔘注意事项：流量用尽后需手动购买流量包或在首页重置流量，不会自动重置。

💰套餐:💰

流量包有自定义选项，自己自由搭配合适的套餐、流量、设备数目，通用的机场面板无这功能。

年付流量加倍

套餐	线路	套餐

⭕️基础	15个节点	140G/月59块/月；200G/月177块/季；240G/月588块/年

⭕️优质	15个节点	160G/月69块/月；220G/月207块/季；280G/月708块/年

⭕️精品	29个节点	180G/月79块/月；240G/月207块/季；320G/月828块/年

─────────────────────────────────────────────────────────────

5.	TAG(154年/200G)
   
⚪️TAG机场是一家IEPL专线中转SS协议机场，提供全球92+国家和地区的节点，拥有大量家宽和商宽原生IP，支持多种流媒体解锁，非常适合流媒体爱好者及需要不同国家IP的用户（如Spotify、ChatGPT等）。TAG精选高带宽、高质量的原生IP节点，线路稳定并逐年升级，广受TG圈内好评。提供140元和154元的年费流量包，适合轻度用户或作为备用选择。

⚫️[TAG 官网地址](https://tagss07.pro/#/auth/WycHb4Kj) 

TAG机场概况

🔘开业时间：2018年，老板位于香港。

🔘入口与过境：入口为深圳，过境采用深港IEPL，协议为Shadowsocks，支持大多数UDP Full Cone。

🔘用户限制：支持最多10台客户端同时使用。

🔘ChatGPT解锁：全面解锁，除香港外基本支持。

🔘节点与落地：覆盖90+国家和地区，220+条线路。家宽地区包括香港、澳门、台湾、新加坡、日本、马来西亚、越南、加拿大、美国等。落地包括香港G-Core商宽、HGC商宽、HKT家宽，日本的软银、KDDI、IDCF等，新加坡Kirino、M1家宽、Whiz家宽等，美国有10余个落地节点，提供不同商宽和家宽节点。

🔘网络设置：节点后端采用负载均衡，精简优化，屏蔽部分墙外新闻网站（轮媒）。SSH端口（10000-65535和22端口）已屏蔽，邮件传统协议（SMTP/POP3/IMAP）被禁止。

🔘适用地区与国际站：仅支持中国大陆内使用，需购买国际站节点才能在国外使用，新疆用户可使用国际站。

🔘支付方式：支持支付宝和虚拟币，套餐费用包含手续费。

🔘客户支持：提供专门客服，TG频道和交流群有1万+人关注，需绑定套餐才能进入群组。

🔘注意事项：流量用尽后需手动续费或重置流量，流量包不可立即重置，需在首页点击“重置”。

💰套餐(除了家宽套餐其他套餐节点一样):💰

套餐	流量	价格

⭕️个人Bronze	250G/月	176块/季

⭕️个人Silver	500G/月	109块/月

⭕️个人Gold	999G/月	209块/月

⭕️特选套餐	200G/年	154块/年，很适合做备用

⭕️团队套餐	3000G/月	627块/月

─────────────────────────────────────────────────────────────

6.	贝贝云(14.9/月100G/月)

⚪️贝贝云机场是一个SS协议中转机场，提供多隧道入口，确保稳定性且避免完全失联。单条带宽适中，足够满足日常需求，适合不希望用户过多的用户。速度表现不错，性价比高。首次购买可使用95折优惠码：beibei.cloud（仅限一次）。

⚫️ [贝贝云 官网地址](beibeilink.top/#/login?code=QalCEjNh) 

贝贝云机场概况

🔘开业时间：2022年，老板位于境外。

🔘入口与过境：入口设在江苏，节点数超30个，采用Shadowsocks协议，支持UDP。

🔘用户限制：允许最多5台设备同时在线。

🔘ChatGPT/OpenAI解锁：除香港节点外，基本全解锁。

🔘流媒体支持：支持奈飞、迪士尼等主流流媒体。

🔘节点与落地：覆盖澳洲、香港、台湾、新加坡、日本、美国、英国、马来西亚、土耳其、阿根廷等地区，落地节点来自Hytron、Akari、PoloCloud、nexeon、Eons、Ipxo LLC、香港HGC等。

🔘网络设置：屏蔽轮媒、rfa、pincong等墙外新闻网站，SSH端口22已屏蔽，传统邮件协议（SMTP/POP3/IMAP）禁止使用，但不影响邮箱官方APP和网页访问。

🔘适用地区：仅限中国大陆使用，新疆用户不可使用。

🔘支付方式：支持支付宝、微信支付，套餐费用不含手续费（手续费6-9%）。

🔘客户支持：提供专门客服，有TG频道但无群组。

🔘一键客户端：无一键客户端。

🔘注意事项：流量用完后需手动续费或重置；首页“重置”按钮可付费重置流量，节点订阅在首页仪表盘的“一键订阅”按钮中。

💰套餐(所有套餐节点数目和速度一样)：💰

流量	价格

⭕️100G/月	14.9/月，42.9/季,提前用完每次重置价格：15块

⭕️200G/月	月付22.9/月，季付62.9,提前用完重置价格：23块

⭕️300G/月	月付32.9,提前用完重置价格：33块

⭕️500G/月	月 付49.9,提前用完重置价格：50块

⭕️1000G/月	月付79.9/,提前用完重置价格：80块

