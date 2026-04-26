# Free VPS Resources

更新时间：2026-04-26  


## 1. VPS / 云主机资源

| 平台 | 免费额度 / 免费形式 | VPS / 实例资源 | 访问网址 | 限制说明 |
|---|---:|---|---|---|
| Oracle Cloud Free Tier | Always Free；另有新账号 $300 试用金 | AMD：最多 2 台 `VM.Standard.E2.1.Micro`；Arm：每月 3,000 OCPU 小时 + 18,000 GB 内存小时，等价约 4 OCPU + 24 GB RAM；Always Free Block Volume 200 GB | https://www.oracle.com/cloud/free/ | Arm A1 容量经常紧张；需要账号验证与支付方式；闲置或违规资源可能被回收 |
| Google Cloud Compute Engine Free Tier | 每月 1 台 `e2-micro` 等量时长 | `e2-micro` 非抢占式 VM；限定 `us-west1`、`us-central1`、`us-east1`；含 30 GB 标准永久磁盘、1 GB 北美出站流量 | https://cloud.google.com/free/docs/free-cloud-features | 只覆盖指定美国区域；GPU/TPU 不在免费层；出站流量额度很小 |
| AWS Free Tier / EC2 | 新用户 Free Plan 最高 $200 credits；EC2 免费层常见为 12 个月 750 小时/月微型实例 | EC2 `t2.micro` / `t3.micro` 等微型实例，具体以账号和区域可用项为准 | https://aws.amazon.com/free/ | AWS Free Plan 与 Paid Plan 规则近年有调整；创建资源前需看 Billing/Free Tier 页面 |
| AWS Lightsail | VPS 3 个月免费 | 1 vCPU、2 GiB RAM、60 GB SSD、3 TB 传输；支持 Linux / Windows / Unix | https://aws.amazon.com/campaigns/aws-cloudserver/ | 3 个月后继续运行会计费；适合网站、轻量后端、测试环境 |
| Microsoft Azure Free Account | 新账号免费服务；VM 页面列出每月 750 小时额度 | B1s、B2pts v2（Arm）、B2ats v2（AMD）突发型 VM 各 750 小时 | https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account | 不同账号类型和地区可用性不同；磁盘、带宽、IP 可能另有计费项 |
| Microsoft Azure for Students | 学生账号免费额度；无需信用卡 | VM 条目同样列出 B1s、B2pts v2、B2ats v2 各 750 小时 | https://azure.microsoft.com/en-us/free/students | 需要学校邮箱/学生身份验证；额度和可用服务按地区与账号状态变化 |
| 阿里云中国站免费试用 | 160+ 云产品免费试用；ECS 试用对计算产品新用户开放 | ECS 最高可试用 4 vCPU / 8 GiB；7 个地域可选；每月流量：中国内地 20 GB + 非中国内地 200 GB | https://free.aliyun.com/ | 需实名认证；每个产品通常只能试用一次；试用 ECS 不支持备案 |
| Alibaba Cloud International Free Trial | 新用户免费试用，页面标注最高可到 12 个月 | ECS 等云产品试用，具体实例与额度按国际站控制台展示 | https://www.alibabacloud.com/en/free | 不同国家/地区权益不同；需绑定支付方式；免费试用政策会动态调整 |
| 腾讯云中国站免费体验馆 | 轻量应用服务器 / CVM 免费试用 | 轻量应用服务器：2核2G/3M/40GB/200GB 流量 1个月；2核4G/5M/60GB/500GB 流量 1个月；4核8G/12M/180GB/2000GB 流量 1个月；CVM 蜂驰型 2核4G/3M/50GB 7天等 | https://cloud.tencent.com/act/pro/free | 需实名认证；部分规格每日限量；备案需购买满足时长要求的包月服务器 |
| Tencent Cloud International Free Tier | Lighthouse / CVM 免费试用 3 个月 | Lighthouse Free Trial 3 months；Cloud Virtual Machine Free Trial 3 months | https://www.tencentcloud.com/act/pro/FreeTier | 具体规格、地域、库存以国际站控制台为准 |
| 华为云中国站 Flexus L 免费体验 | Flexus 应用服务器 L 实例免费体验 | 轻量级云服务器，活动库存配置；常见活动资源为 Flexus L / ECS 类实例 | https://www.huaweicloud.com/special/pro-aos-free.html | 单个产品限领一次；库存有限，领完为止；具体 CPU/内存/带宽以登录后的领取页为准 |
| HUAWEI CLOUD International Free Packages | 15 款云服务合计 1500 小时免费试用 | 包含 Elastic Cloud Server（ECS）、EIP、EVS、RDS 等 | https://activity.huaweicloud.com/intl/en-us/free_packages/ME.html | 页面要求企业账号、有效支付方式；支持 Visa / Mastercard |
| IBM Cloud Free / PowerVS Credit | Lite 计划长期免费；PowerVS / VPC 环境可领试用 credit | IBM Cloud 页面列出 PowerVS 与 VPC supporting services 最高 $2,500 credits / 90 天 | https://www.ibm.com/products/cloud/free | 普通虚拟服务器不是长期免费 VPS；适合测试 IBM Cloud / PowerVS / VPC 环境 |
| DigitalOcean Free Trial | 新账号 $200 credits / 60 天 | Droplets VPS、Managed DB、Kubernetes、App Platform 等 | https://www.digitalocean.com/ | 需新账号；试用金到期或用尽后继续运行会计费 |
| Akamai Cloud / Linode | $100 cloud credit | Linode Compute / VPS 等 Akamai Cloud 服务 | https://www.akamai.com/lp/free-credit-100 | 试用金形式；需要注册账号；具体可用产品以 Akamai Cloud 控制台为准 |
| Vultr | 官方优惠页提供 free credit 活动 | Vultr Cloud Compute / VPS；当前优惠页显示可试用 $200 free credit | https://www.vultr.com/coupons/ | Promotional credit 仅适用于部分产品；活动金额和有效期可能变化 |
| OVHcloud Public Cloud Free Trial | US$200 credits / 1 个月 | Public Cloud Instances，可创建云服务器；示例包括 B2 系列实例、Kubernetes、AI Notebook 等 | https://www.ovhcloud.com/asia/public-cloud/free-trial/ | 需创建首个 Public Cloud project；需添加支付方式；试用金耗尽后会自动按支付方式计费 |
| Scaleway | €100 free credit | Scaleway Instances、存储、数据库等云资源 | https://www.scaleway.com/en/scaleway-vs-digitalocean/ | 页面面向 Professional / Business account；具体可用范围按账号类型 |
| Civo | $250 credits / 1 个月 | Kubernetes clusters、individual virtual machine instances、Volumes 等 | https://www.civo.com/ | 需在注册后添加信用卡；credit 可用于 Civo 任意服务 |
| Kamatera | $100 / 30 天免费试用 | 1 台 cloud server，可自选数据中心、OS、CPU、RAM、存储；另含 1 TB block storage、1 TB 流量 | https://www.kamatera.com/free-trial/ | 需有效信用卡；超出 $100 或 30 天后会计费 |
| AccuWeb Cloud | $100 credits / 30 天 | Cloud VPS、数据库、应用、存储等 | https://accuweb.cloud/free | 云平台试用金；适合短期 VPS/云应用测试 |
| AccuWeb Windows VPS | Windows VPS 30 天免费试用 | Windows Server 2019；USA Denver location；Remote Desktop + root/admin access | https://www.accuwebhosting.com/vps-hosting/windows/free-vps | 新用户一次；人工审核 24–48 小时；无需信用卡；仅 Windows VPS |

## 2. VPS 替代：免费容器、Web Service、SSH 运行环境

| 平台 | 免费额度 / 免费形式 | 可用资源 | 访问网址 | 限制说明 |
|---|---:|---|---|---|
| Koyeb Free Instance | 每个组织 1 个 Free Instance | 512 MB RAM、0.1 vCPU、2 GB SSD | https://www.koyeb.com/docs/reference/instances | Web Service 形态，非传统 VPS；不适合生产 |
| Render Free Web Service | Free Web Service，$0/月 | 512 MB RAM、0.1 CPU；支持 Node、Python、Go、Rust、Ruby、Elixir、Docker | https://render.com/pricing | 空闲 15 分钟会休眠；文件系统为临时文件系统 |
| Railway Free | 30 天 $5 credits，之后每月 $1 free credit | 试用期最高 2 vCPU / 1 GB RAM；试用后最高 1 vCPU / 0.5 GB RAM；0.5 GB volume | https://railway.com/pricing | 免费期后额度很小；更像 PaaS，不提供完整 root VPS |
| Serv00 | 长期免费 hosting account | 3 GB SSD、无限流量、最多 100 个网站、16 个数据库；支持 SSH、cron、PHP、Python、Node.js、Ruby、Java、.NET、MySQL、PostgreSQL、MongoDB | https://www.serv00.com/ | 共享主机/FreeBSD 环境，非 root VPS；违规代理、隧道等用途容易被封 |
| GitHub Codespaces | GitHub Free 个人账号每月 120 core-hours + 15 GB storage | 云端开发容器；2-core codespace 约 60 小时/月 | https://docs.github.com/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces | 开发环境，非公网常驻 VPS；组织仓库可能由组织或个人账户计费 |
| Google Cloud Shell | 免费 Cloud Shell + 5 GB persistent disk | 浏览器 Linux shell，`$HOME` 5 GB 持久化存储 | https://cloud.google.com/free/docs/free-cloud-features | 临时 Shell，不适合常驻服务；会话和周/月配额有限 |
| AWS CloudShell | 免费 CloudShell；每区域 1 GB persistent storage | 1 vCPU、2 GiB RAM、1 GB 持久化 `$HOME` | https://docs.aws.amazon.com/cloudshell/latest/userguide/vm-specs.html | 管理型临时 Shell，非 VPS；会话结束后系统层改动不持久化 |
| Oracle Cloud Shell | 免费 Cloud Shell | 5 GB persistent storage | https://docs.oracle.com/iaas/Content/API/Concepts/cloudshellintro.htm | 主要用于管理 OCI；非公网常驻服务 |
| Azure Cloud Shell | Cloud Shell 机器免费 | Bash / PowerShell；通常使用 Azure Files 挂载 `$HOME` | https://learn.microsoft.com/en-us/azure/cloud-shell/overview | Cloud Shell 机器免费，但存储账号可能产生常规存储费用 |

## 3. 快速筛选

| 需求 | 优先查看的平台 |
|---|---|
| 长期免费、接近真实 VPS | Oracle Cloud Always Free、Google Cloud Compute Engine Free Tier |
| 短期高配 VPS 测试 | Tencent Cloud 免费体验馆、阿里云免费试用、Huawei Cloud Free Packages、Kamatera、OVHcloud、DigitalOcean |
| 无信用卡或低门槛体验 | Serv00、GitHub Codespaces、Railway Free、AccuWeb Windows VPS |
| 国内实名云服务器试用 | 阿里云、腾讯云、华为云 |
| 海外云服务器试用金 | DigitalOcean、Akamai/Linode、Vultr、OVHcloud、Scaleway、Civo、Kamatera |
| 只需要临时 Linux Shell | Google Cloud Shell、AWS CloudShell、Oracle Cloud Shell、Azure Cloud Shell |

## 4. 来源链接

- Oracle Cloud Free Tier: https://www.oracle.com/cloud/free/
- Oracle Always Free resources: https://docs.oracle.com/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm
- Google Cloud Free Program: https://cloud.google.com/free/docs/free-cloud-features
- AWS Free Tier: https://aws.amazon.com/free/
- AWS Lightsail campaign: https://aws.amazon.com/campaigns/aws-cloudserver/
- Microsoft Azure Free Account: https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account
- Microsoft Azure for Students: https://azure.microsoft.com/en-us/free/students
- 阿里云免费试用: https://free.aliyun.com/
- Alibaba Cloud Free Trial: https://www.alibabacloud.com/en/free
- 腾讯云免费体验馆: https://cloud.tencent.com/act/pro/free
- Tencent Cloud Free Tier: https://www.tencentcloud.com/act/pro/FreeTier
- 华为云 Flexus L 免费体验: https://www.huaweicloud.com/special/pro-aos-free.html
- HUAWEI CLOUD Free Packages: https://activity.huaweicloud.com/intl/en-us/free_packages/ME.html
- IBM Cloud Free: https://www.ibm.com/products/cloud/free
- DigitalOcean: https://www.digitalocean.com/
- Akamai Cloud $100 Credit: https://www.akamai.com/lp/free-credit-100
- Vultr Coupons: https://www.vultr.com/coupons/
- OVHcloud Public Cloud Free Trial: https://www.ovhcloud.com/asia/public-cloud/free-trial/
- Scaleway: https://www.scaleway.com/
- Civo: https://www.civo.com/
- Kamatera Free Trial: https://www.kamatera.com/free-trial/
- AccuWeb Cloud Free Trial: https://accuweb.cloud/free
- AccuWeb Windows VPS Free Trial: https://www.accuwebhosting.com/vps-hosting/windows/free-vps
- Koyeb Free Instance: https://www.koyeb.com/docs/reference/instances
- Render Pricing: https://render.com/pricing
- Render Free Services: https://render.com/docs/free
- Railway Pricing: https://railway.com/pricing
- Serv00: https://www.serv00.com/
- GitHub Codespaces billing: https://docs.github.com/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces
- Google Cloud Shell: https://docs.cloud.google.com/shell/docs/using-cloud-shell
- AWS CloudShell VM specs: https://docs.aws.amazon.com/cloudshell/latest/userguide/vm-specs.html
- Oracle Cloud Shell: https://docs.oracle.com/iaas/Content/API/Concepts/cloudshellintro.htm
- Azure Cloud Shell: https://learn.microsoft.com/en-us/azure/cloud-shell/overview
