# Holtwood Projects

从零构建、可直接运行的完整项目：Web、GPU、系统工具与教学实现。

维护者：[holtwood](https://github.com/holtwood)

## 这里放什么

clone 下来、按 README 就能跑起来的完整项目，大致三类：

- **工具**：解决实际使用中的问题，本地优先，数据尽量不出设备
- **教学实现**：把经典算法或系统从零写一遍，代码结构优先于功能数量
- **GPU / 高性能**：CUDA、WebGPU、数值计算，附基准与复现步骤

AI Infra 系统项目在 [open-infra-ai](https://github.com/open-infra-ai)，上游研读副本在 [holtwood-forks](https://github.com/holtwood-forks)。

## 工具

| 仓库 | 说明 |
|------|------|
| [bookmarks-manager](https://github.com/holtwood-projects/bookmarks-manager) | 纯前端书签整理 PWA，无后端，数据不出浏览器 |
| [bookmarks-cleaner](https://github.com/holtwood-projects/bookmarks-cleaner) | 离线书签自动分类：规则优先，LLM 可选 |
| [mind-gym](https://github.com/holtwood-projects/mind-gym) | 浏览器端认知训练：N-back、间隔重复、自适应难度 |
| [graph-viewer](https://github.com/holtwood-projects/graph-viewer) | 16 种图表引擎的统一查看器 |
| [utop](https://github.com/holtwood-projects/utop) | Rust 终端进程监视器，教学向 htop 实现 |
| [dig-your-windows](https://github.com/holtwood-projects/dig-your-windows) | Windows 硬件、SMART 与事件日志诊断 |
| [compress-kit](https://github.com/holtwood-projects/compress-kit) | C++17 实现 Huffman、算术、区间、RLE、LZSS |
| [bitcal](https://github.com/holtwood-projects/bitcal) | 纯头文件 C++23 位运算库，x86-64 + AVX2 |
| [cmdc-statusline](https://github.com/holtwood-projects/cmdc-statusline) | Command Code 的状态栏：模型、上下文、成本、git 状态 |
| [cloud-bench](https://github.com/holtwood-projects/cloud-bench) | 云服务器性能评测脚本与方法论 |
| [wb2api](https://github.com/holtwood-projects/wb2api) | 把 CodeBuddy 订阅包成 OpenAI 兼容接口（非官方） |

## 浏览器与实时通信

| 仓库 | 说明 |
|------|------|
| [webrtc-call](https://github.com/holtwood-projects/webrtc-call) | 浏览器原生 P2P 音视频通话（1v1 / Mesh），配套 Go 信令 |
| [webrtc-signaling](https://github.com/holtwood-projects/webrtc-signaling) | Go 信令服务：JWT、Redis Pub/Sub、Prometheus |
| [chatroom](https://github.com/holtwood-projects/chatroom) | Go + React + PostgreSQL + WebSocket 全栈教学 |

## GPU 与数值计算

| 仓库 | 说明 |
|------|------|
| [nbody-gpu-sim](https://github.com/holtwood-projects/nbody-gpu-sim) | CUDA 百万粒子 N 体模拟：Direct N² / Barnes-Hut / Spatial Hash |
| [cudaimg](https://github.com/holtwood-projects/cudaimg) | 用图像处理算子入门 CUDA |
| [gpu-spmv](https://github.com/holtwood-projects/gpu-spmv) | CSR + ELL 的 SpMV 库：四种内核、自动选核、基准 |
| [webgpu-sorting](https://github.com/holtwood-projects/webgpu-sorting) | WebGPU 计算着色器排序，含分块扫描修正与回归 |

## 应用

| 仓库 | 说明 |
|------|------|
| [JadeAI](https://github.com/holtwood-projects/JadeAI) | 简历编辑与求职工作台：模板、解析、JD 匹配、导出 |
| [meta-human](https://github.com/holtwood-projects/meta-human) | 浏览器 3D 数字人，集成语音与对话 |
| [yolo-toys](https://github.com/holtwood-projects/yolo-toys) | YOLOv8 / DETR / OWL-ViT / Grounding DINO / BLIP 的统一 FastAPI 接口 |
| [shadow-note](https://github.com/holtwood-projects/shadow-note) | 端到端加密笔记同步，服务端零知识 |
| [chat-stash](https://github.com/holtwood-projects/chat-stash) | 保存 AI 聊天记录的 Chrome 扩展，Supabase 存储与全文检索 |

## 站点

组织门户：[holtwood-projects.github.io](https://holtwood-projects.github.io/)

## 约定

- 每个仓库的 README 说明用途、运行方式与已知限制
- 教学项目优先保证代码可读，不追求功能数量
- 性能数字附硬件、命令与复现方式；没有测量就不写结论
