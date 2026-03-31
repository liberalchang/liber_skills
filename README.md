# liber_skills
个人技能集合（skills）。每个 skill 独立维护，包含自己的 `SKILL.md` 使用说明与脚本/资源文件。

**仓库地址**：https://github.com/liberalchang/liber_skills.git

**项目描述**：个人开发的 skill 合集

## Skills 列表

### skill-python-env

- **名称**：`skill-python-env`
- **描述**：管理 OpenClaw skill 的 Python 虚拟环境。在 `~/.python_env/<env_name>` 下检查、创建环境；自动安装 uv（若未安装）。供其他需要 Python 环境的 skill 调用。
- **版本**：`1.0.0`
- **目录**：`skill-python-env/`

### frontendslides

- **名称**：`frontend-slides`
- **描述**：从零开始创建或转换 PowerPoint 文件，生成精美的动画丰富 HTML 演示文稿。适用于用户想要制作演示文稿、将 PPT/PPTX 转换为网页，或为演讲/推介创建幻灯片的场景。帮助非设计者通过视觉探索而非抽象选择来发现美学风格。
- **版本**：`1.0.0`
- **目录**：`frontendslides/`

### barkpush

- **名称**：`bark-push`
- **描述**：智能 Bark 推送助手，支持多用户管理、智能内容识别、历史记录追踪和消息更新功能
- **版本**：`1.2.0`
- **目录**：`barkpush/`

### nano-banana-pro-openrouter

- **名称**：`nano-banana-pro`
- **描述**：通过 OpenRouter 使用 Nano Banana Pro（Gemini 3 Pro Image）生成/编辑图像。适用于图像创建/修改请求，包括编辑功能。支持文本生成图像、图像生成图像；支持 1K/2K/4K 分辨率；使用 --input-image 参数进行图像编辑。
- **版本**：`v1.0.0`
- **目录**：`nano-banana-pro-openrouter/`

## 安装方法（参考 Clawhub）

### 方式 A：从 Clawhub 商店安装（上架后）

- **步骤 1**：安装/配置 Clawhub（或 OpenClaw）客户端
- **步骤 2**：使用 `clawhub search <skill-name>` 搜索 skill，然后使用 `clawhub install <skill-name>` 安装
- **步骤 3**：按每个 skill 的 `SKILL.md` 完成必要配置（例如环境变量、配置文件、state 目录等）

### 方式 B：本地安装（当前仓库）

- **步骤 1**：克隆本仓库到本地
- **步骤 2**：把需要的 skill 目录复制/链接到你的 skills 目录（例如 `~/.openclaw/skills/`）
- **步骤 3**：进入对应目录阅读 `SKILL.md`，按说明运行脚本或命令

## 版本信息说明

当前版本按你的约定为：

- `skill-python-env`：`1.0.0`
- `frontendslides`：`1.0.0`
- `barkpush`：`1.2.0`
- `nano-banana-pro-openrouter`：`v1.0.0`
