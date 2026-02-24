# CNN-Visualization-and-Fault-Tolerant-Convolution
cat << 'EOF' > README.md
This project explores convolutional neural networks (CNNs), feature visualization, filter learning, and fault-tolerant verification using checksum schemes.

## 🔹 Key Topics Covered

- Convolution mechanics (filters = output channels)
- Kernel, stride, and pooling variations
- MNIST single-filter experiments
- Gradient descent-based filter learning (MSE + SGD)
- Deep feature visualization (VGG16, VGG19, ResNet50, ResNet50V2)
- Layer-wise filter analysis & duplicate detection
- Weight change analysis (inference vs training)
- Checksum-based fault-tolerant CNN validation

## 🔹 Core Findings

- Convolution is distributive over inputs and filters.
- Pretrained CNNs contain no duplicate filters.
- Early layers detect edges; deeper layers capture abstractions.
- Inference does not modify weights.
- Filters can be learned effectively via gradient descent.
- Checksum schemes verify convolution correctness.

## 🛠 Tech Stack

- Python
- PyTorch
- TensorFlow / Keras
- NumPy
- Matplotlib

## 🚀 Run

git clone <repo-link>
cd project-folder
pip install -r requirements.txt
python main.py

EOF
