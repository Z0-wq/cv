# Status（当前状态，日常更新）

## 当前推进
- 阶段：**阶段四（机器学习与深度学习原理）已全部完成**✅
- 下一步：阶段五 目标检测与YOLO系列（6.1任务分类概念 → 6.2检测核心概念 → 6.3检测网络发展脉络 → 6.4YOLO环境搭建Demo → 6.5数据标注 → 6.6自定义训练 → 6.7结果分析）

## 待办
- 阶段五：YOLO系列全部节点
- 遗留：一道融合3.1/3.2/3.5的综合编程练习题（读图→灰度→高斯滤波→ORB关键点→打印shape），待补做

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
