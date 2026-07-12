# CV 自学之旅

电子信息工程专业学生的计算机视觉自学记录：从Python零基础，到Python基础 → 数学基础 → OpenCV传统视觉 → 深度学习原理(PyTorch) → YOLO目标检测的完整学习过程与代码实践。

## 项目结构

- `overview.md`：学习总纲，目标、学习方式、核心知识路线
- `roadmap.md`：详细知识节点规划（含各阶段目标、知识点、参考资料）
- `status.md`：当前学习进度
- `note.md`：已掌握知识点归档（含例题、参考答案、易错总结）
- `rule.md`：协作规则约束
- `yolo_test.ipynb`：YOLO目标检测实操示例

## 环境要求

- Python 3.11
- 依赖库见 `requirements.txt`
- GPU版PyTorch需根据自己的显卡/CUDA版本单独安装，参考 [PyTorch官网](https://pytorch.org/get-started/locally/)

## 使用方法

```bash
# 创建并激活虚拟环境（conda示例）
conda create -n cv python=3.11
conda activate cv

# 安装依赖
pip install -r requirements.txt
```

YOLO推理示例（`yolo_test.ipynb`）：

```python
from ultralytics import YOLO

model = YOLO("yolo11n.pt")   # 首次运行会自动下载模型权重
results = model("你的图片路径.jpg")
results[0].show()
```

## 效果展示

已跑通YOLO官方预训练模型的图片推理与摄像头实时检测，详见 `yolo_test.ipynb`。
