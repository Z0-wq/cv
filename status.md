# Status（当前状态，日常更新）

## 当前推进
- 阶段：阶段六 综合项目与部署
- 知识点：7.1 摄像头实时推理集成✅已归档；下一子模块：7.2嵌入式部署（可选，需确认硬件条件）

## 当前推进
- 阶段：阶段六 综合项目与部署
- 知识点：7.3 项目文档化与GitHub整理✅已归档（含实操：requirements.txt/.gitignore/README.md已生成修正）
- 7.2嵌入式部署**待定暂缓**（用户倾向买"庐山派"K230，未下单，确认购买后回来补）

## 待办
- **暑假主线规划(阶段一~六)已全部完成**，仅剩7.2嵌入式部署待硬件购买后补充
- 阶段七"进阶方向"已写入roadmap.md：部署实用向主线(模型量化/ONNX/TensorRT) + 论文理论向路径说明，视情况推进
- 遗留：一道融合3.1/3.2/3.5的综合编程练习题（读图→灰度→高斯滤波→ORB关键点→打印shape），待补做
- **待推送**：requirements.txt生成修正、.gitignore、README.md重写、note.md/status.md更新，共这几项本地已完成但代理不稳定尚未push到GitHub（多次测试SSL握手失败，非我方配置问题）

## 环境配置记录（补充）
- cv环境已装ultralytics 8.4.92（YOLO库）

## 环境配置记录（补充）
- cv环境已装GPU版PyTorch 2.6.0+cu124 + torchvision 0.21.0+cu124，torch.cuda.is_available()=True，GPU为RTX 4060 Laptop

## 环境配置记录（供查阅，非知识点）
- 原Anaconda(C:\Users\rog\anaconda3)安装不完整，已弃用不删除
- Miniconda已装在 **D:\CV**（用户指定路径，非C盘），已conda init bash
- 已建环境`cv`（Python 3.11），已装numpy/matplotlib/opencv-python/jupyter/ipykernel
- 日常使用：新开终端先 `conda activate cv`
- VS Code已装Python+Jupyter插件，解释器需手动输入路径 D:\CV\envs\cv\python.exe（因装在非默认路径，插件不会自动扫到）
- GitHub账号：Z0-wq，仓库 https://github.com/Z0-wq/cv.git 已建立并push成功
- **git已配置全局代理**(http/https.proxy均为127.0.0.1:7897)，push/pull前必须先打开本地代理软件

## 注意事项
- 无

## 已完成里程碑
- 无
