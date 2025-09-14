Container Damage Detection using Image Processing
An automated system to detect and classify surface damage on containers using computer vision and deep learning, designed to optimize the inspection process and reduce costs.

1. Project Overview
This project introduces a cost-effective system for container damage detection, leveraging the YOLOv8 model and integrating it into a web-based platform.

Objective: To automate container inspection, replacing manual and time-consuming methods. This approach enhances accuracy and significantly reduces the time required for checks.

Problem Addressed: Traditional inspection methods are costly, inefficient, and inaccessible for many small and medium-sized enterprises (SMEs) in Vietnam due to high investment costs. This solution addresses this issue by using a Raspberry Pi 4 to create an affordable and efficient system.

Features: The system can detect common damages such as holes, rust, and dents, adhering to IICL standards. It also supports repair cost estimation and data storage on a web and mobile application platform.

2. Technologies & Hardware
Programming Languages: Python, C++

Deep Learning Model: YOLOv8m.pt

Libraries: OpenCV, NumPy, EasyOCR (for container number recognition)

Hardware:

Microcontroller: Raspberry Pi 4 Model B

Camera: Raspberry Pi Camera V2 IMX219

Communication: Tailscale (VPN), SSH Remote

Web Framework: Python Flask

3. System Architecture
The system operates according to the following workflow:

Image Capture: A technician uses a camera connected to the Raspberry Pi 4 to take photos of the container.

Data Processing: The images are transferred from the Raspberry Pi 4 to a server for analysis using the pre-trained YOLOv8 model.

Result Display: Detection results (damage location, type, and container number) are sent back and visualized on a monitor or a web interface.

Management & Reporting: Damage data is stored on the server, facilitating repair cost estimation and management through the web interface.

4. Results & Evaluation
The system has demonstrated significant performance in automating the inspection process.

Precision: 84.2%

Recall: 71.1%

Model: Trained on a diverse dataset of 13,827 images.

Effectiveness: The solution successfully delivers a low-cost system, making it suitable for SMEs, with high potential for widespread application in the logistics industry.

5. Authors
Duy Anh Do

Le Minh Khoi Pham
