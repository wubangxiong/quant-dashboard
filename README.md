# 量化分析仪表盘 (Quant Dashboard)

一个纯前端的实时量化信号引擎 + AI 事件推演分析仪表盘。**单文件、零后端、零依赖安装**，下载即可运行。

## 一、快速运行（二选一）

### 方式 1：直接双击
在文件资源管理器中双击 `index.html`，用浏览器（Chrome / Edge）打开即可。

### 方式 2：本地服务器（推荐，体验更完整）
在项目目录打开终端，运行：

```bash
python -m http.server 8000
```

然后浏览器访问：<http://localhost:8000>

> 没有 Python？也可以用 Node.js：
>
> ```bash
> npx serve .
> ```

## 二、配置你的 DeepSeek API Key（AI 功能必需）

AI 策略生成、热点事件推演等功能依赖 DeepSeek 大模型，**需要填入你自己的 API Key**（本项目不内置任何 Key）：

1. 打开 <https://platform.deepseek.com> 注册并创建 API Key（格式 `sk-...`）
2. 打开页面后，点击右下角「⚙ API 设置」
3. 粘贴你的 Key，点击「保存并使用」

> Key 只保存在你本地浏览器（localStorage），不会上传到任何服务器。

## 三、让 AI 助手（豆包 / TraeCode 等）帮你一键部署

把下面这段话直接发给你的 AI 助手，它就能自动帮你部署到本机：

> 请克隆仓库 `https://github.com/wubangxiong/quant-dashboard.git`，
> 然后进入项目目录运行 `python -m http.server 8000`，
> 最后打开 http://localhost:8000 预览。

## 四、项目结构

```
.
├── index.html   # 全部功能都在这个文件里
└── README.md    # 本说明
```

## 五、联系作者

- QQ 交流群：`436722844`
- QQ：`207442662`
