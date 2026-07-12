# Status（当前状态，日常更新）

## 当前推进
- 阶段：**阶段七主线A（部署实用向）已全部完成**✅（模型量化/ONNX导出/TensorRT设备优化）
- 下一步：🏆进阶项目——把阶段六检测项目做量化+格式转换，实际部署到真实边缘设备，对比量化前后速度/精度差异（需硬件，可结合"庐山派"K230购买后进行）

## 待办
- 进阶项目：等K230到手后进行实际部署对比
- 主线B（论文理论向）路径已写入roadmap.md，暂不列入正式学习，需要时自学
- 7.2嵌入式部署仍待定（同上，等K230购买）
- 遗留：一道融合3.1/3.2/3.5的综合编程练习题（读图→灰度→高斯滤波→ORB关键点→打印shape），待补做
- 注意：上次status.md在GitHub网页端直接编辑过，下次push前需先pull同步，避免冲突
- 7.2嵌入式部署**待定暂缓**（用户倾向买"庐山派"K230，未下单，确认购买后回来补，可与阶段七部署内容结合）
- 遗留：一道融合3.1/3.2/3.5的综合编程练习题（读图→灰度→高斯滤波→ORB关键点→打印shape），待补做
- 注意：上次status.md在GitHub网页端直接编辑过，下次push前需先pull同步，避免冲突

## 环境配置记录（供查阅，非知识点）
- 原Anaconda(C:\Users\rog\anaconda3)安装不完整，已弃用不删除
- Miniconda已装在 **D:\CV**（用户指定路径，非C盘），已conda init bash
- 已建环境`cv`（Python 3.11），已装numpy/matplotlib/opencv-python/jupyter/ipykernel
- 日常使用：新开终端先 `conda activate cv`
- VS Code已装Python+Jupyter插件，解释器需手动输入路径 D:\CV\envs\cv\python.exe（因装在非默认路径，插件不会自动扫到）
- GitHub账号：Z0-wq，仓库 https://github.com/Z0-wq/cv.git 已建立并push成功
- **git已配置全局代理**(http/https.proxy均为127.0.0.1:7897)，push/pull前必须先打开本地代理软件
- cv环境已装ultralytics 8.4.92（YOLO库）
- cv环境已装GPU版PyTorch 2.6.0+cu124 + torchvision 0.21.0+cu124，torch.cuda.is_available()=True，GPU为RTX 4060 Laptop

## 注意事项
- 无

## 已完成里程碑
- 无
