# iPhone 侧载工具合集（合法开源工具）

> **免责声明**  
> 本文件仅整理公开、开源的合法侧载工具，用于个人开发测试或安装自己的应用。  
> - 使用免费 Apple ID 签名的应用有效期通常为 **7 天**，且同时最多安装约 **3 个应用**。  
> - 请遵守当地法律法规和 Apple 服务条款。  
> - 不要从非官方渠道下载 IPA 或证书，容易中毒或被封号。  
> - 本仓库不提供任何破解应用、盗版 IPA 或企业证书。

更新时间：2026-09-11

---

## 一、目前推荐的主流工具（2026 年）

### 1. SideStore（目前最推荐的免费方案）
- **特点**：安装后基本不需要电脑，可在设备上自动刷新签名
- **适用**：iOS 15 及以上（包括较新的 iOS 26）
- **限制**：免费 Apple ID 仍是 7 天签名 + 3 个应用限制
- 官方网站：https://sidestore.io/
- GitHub：https://github.com/SideStore/SideStore

### 2. AltStore（经典稳定方案）
- **特点**：需要电脑上的 AltServer 配合刷新（可通过 Wi-Fi）
- **适用**：广泛兼容
- GitHub：https://github.com/altstoreio/AltStore
- 官网：https://altstore.io/

### 3. Sideloadly（电脑端最简单的工具）
- **特点**：Windows / Mac 拖拽 IPA 即可安装，支持注入插件
- **适用**：适合偶尔安装几个应用的用户
- 官网：https://sideloadly.io/

### 4. iloader（安装 SideStore 的辅助工具）
- **特点**：帮助更方便地安装 SideStore，支持 Windows / macOS / Linux
- 官网：https://iloader.app/
- GitHub：https://github.com/nab138/iloader

### 5. SideInstaller（纯设备端安装 SideStore）
- **特点**：尝试在手机上直接安装 SideStore（无需电脑）
- GitHub：https://github.com/FrizzleM/SideInstaller
- 官方页面：https://frizzlem.github.io/SideInstaller/

### 6. TrollStore（永久安装，仅限旧系统）
- **特点**：利用漏洞实现永久签名，无需刷新
- **重要限制**：只支持 **iOS 14.0 ~ 17.0**，更高系统已失效
- GitHub：https://github.com/opa334/TrollStore

---

## 二、简单选择建议

| 你的情况                     | 推荐工具              |
|-----------------------------|-----------------------|
| 想尽量少用电脑               | SideStore             |
| 有电脑，追求稳定             | AltStore 或 Sideloadly |
| 系统是 iOS 17.0 及以下       | 优先考虑 TrollStore   |
| 只是临时装一两个应用         | Sideloadly            |
| 想在手机上完成安装           | SideInstaller / iloader |

---

## 三、使用提醒

1. **强烈建议使用小号 Apple ID** 进行签名，不要用主力账号。
2. 免费账号每周可创建的 App ID 数量有限，装太多会提示无法注册。
3. 签名过期后应用会打不开，需要刷新（SideStore / AltStore 可自动处理）。
4. 不要去搜「企业证书」「Scarlet」「全能签」之类来路不明的源，风险很高。
5. 想装更多应用或更久有效期，只能考虑付费开发者账号（99 美元/年）或正规付费签名服务。

---

## 四、相关文件

本仓库其他文件：
- [free-nodes.md](./free-nodes.md) — 免费公开节点订阅
- [README.md](./README.md) — 仓库介绍

有需要我可以继续补充详细安装教程（按不同工具分步骤写）。
