.<h1 align="center">🔧 Hardware Requirements 🖥️</h1>
|          |                                         |
| ----------------------------- | --------------------------------------- |
| Computer System:              | - High-performance desktop or server-grade computer for real-time processing.    |
|                               | - A multi-core CPU (e.g., Intel Core i7 or higher) for efficient computations.    |
|                               | - Sufficient RAM (e.g., 16GB or more) to handle image processing tasks.           |
|                               | - A dedicated GPU (e.g., NVIDIA GeForce GTX 1060 or higher) for accelerated deep learning inference. |
| High-Resolution Cameras:      | - High-resolution cameras capable of capturing clear images of license plates. Resolution should be at least 1080p or higher. |
| Storage:                      | - Fast and ample storage space, preferably SQL, for storing recorded video footage and processed data. |
| Network Infrastructure:       | - A reliable network connection, preferably wired, to transfer data and communicate with other devices if needed. |

.<h1 align="center">📋 Software Requirements 🖥️</h1>
|          |                                         |
| ----------------------------- | --------------------------------------- |
| Operating System:             | - A modern operating system such as Windows 10, Ubuntu 20.04 LTS, or CentOS 8, depending on your preference and compatibility with the required software. |
| Programming Language:         | - Python 3.x Python for developing the tracking camera software. |
| Image Processing Library:     | - OpenCV: An open-source computer vision library that will be essential for image and video processing. |
| Deep Learning Framework:      | - YOLOv8: The specific deep learning model for object detection and license plate recognition. PyTorch or TensorFlow implementation of YOLOv8. |
| Classification Technique:     | - YOLOv8 typically handles object detection rather than classification. However, you may use additional techniques, such as OCR (Optical Character Recognition), for license plate text recognition. |
| Integrated Development Environment (IDE): | - Options include Visual Studio Code, PyCharm, or Jupyter Notebook. |
| Dataset:                      | - Dataset of labeled license plates for training and testing YOLOv8 model. Specifications for the dataset may include a variety of license plate images captured in different lighting conditions, angles, and backgrounds. |

  
<h1 align="center">📚 Resources 🖥️</h1>

## System Architecture:

![Data Flow Diagram](/assets/LPR/system-architecture.png)

## Database Structure:

![Data Flow Diagram](/assets/LPR/database-schema.png)