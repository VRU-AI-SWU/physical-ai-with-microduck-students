# Physical AI with Microduck — Lab notebooks สำหรับผู้เรียน

[![English](https://img.shields.io/badge/lang-English-lightgrey)](README.en.md) [![ภาษาไทย](https://img.shields.io/badge/lang-%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2%E0%B9%84%E0%B8%97%E0%B8%A2-red)](README.md)

Notebook ประกอบคลิป YouTube ชุด *Physical AI with Microduck* ของวิชา Introduction to Physical AI ตั้งแต่ coordinate, MuJoCo และ PD control ไปจนถึง Reinforcement Learning ที่ train ให้ bipedal robot Microduck เดิน

📖 **อ่านเนื้อหาบทเรียนออนไลน์:** https://vru-ai-swu.github.io/physical-ai-with-microduck-students/

แต่ละ lab ที่มี code มี 2 ไฟล์ (lab ที่ไม่มี code เช่น EP01 Lab 1 บน browser มี notebook เดียว)

- **✏️ Starter** — โค้ดส่วนใหญ่เตรียมไว้แล้ว ดูคลิปแล้วเติมเฉพาะจุด `✏️ TODO` ทุกจุดบอกเวลาในคลิปที่อธิบายโค้ดตรงนั้น
- **✅ เฉลย** — โค้ดชุดเดียวกับในคลิป รันได้ทันที ใช้เทียบเมื่อติด

🇬🇧 **English:** [README in English](README.en.md) · notebook ภาษาอังกฤษ (`.en.ipynb`) อยู่ในโฟลเดอร์เดียวกัน

## เริ่มต้น

1. กดปุ่ม **Open in Colab** ของ lab ที่ต้องการ (หรือดาวน์โหลด `.ipynb` ไปเปิดใน Jupyter บนเครื่อง)
2. รันทุก cell จากบนลงล่าง cell แรกติดตั้ง package ที่ lab ต้องใช้ให้เอง

Lab ของ Microduck (EP10–EP13) train ด้วย GPU ใน notebook จะใช้ checkpoint ที่เตรียมไว้แทน

## EP01 Physical AI คืออะไร

| Lab | ✏️ Starter | ✅ เฉลย | 🇬🇧 English |
|---|---|---|---|
| Lab 1 — ขับ Microduck ใน browser | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab1-browser-sim.ipynb) · [ไฟล์](ep01-what-is-physical-ai/ep01-lab1-browser-sim.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab1-browser-sim.ipynb) · [ไฟล์](ep01-what-is-physical-ai/ep01-lab1-browser-sim.ipynb) | [starter](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab1-browser-sim.en.ipynb) · [solution](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab1-browser-sim.en.ipynb) |
| Lab 2 — Python, Git และ Colab | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab2-python-git-colab.student.ipynb) · [ไฟล์](ep01-what-is-physical-ai/ep01-lab2-python-git-colab.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab2-python-git-colab.ipynb) · [ไฟล์](ep01-what-is-physical-ai/ep01-lab2-python-git-colab.ipynb) | [starter](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab2-python-git-colab.en.student.ipynb) · [solution](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab2-python-git-colab.en.ipynb) |
| Lab 3 — เปิดตัว Microduck ใน MuJoCo แล้วดูมันล้ม | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab3-meet-microduck.student.ipynb) · [ไฟล์](ep01-what-is-physical-ai/ep01-lab3-meet-microduck.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab3-meet-microduck.ipynb) · [ไฟล์](ep01-what-is-physical-ai/ep01-lab3-meet-microduck.ipynb) | [starter](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab3-meet-microduck.en.student.ipynb) · [solution](https://colab.research.google.com/github/VRU-AI-SWU/physical-ai-with-microduck-students/blob/main/ep01-what-is-physical-ai/ep01-lab3-meet-microduck.en.ipynb) |

## License

code ใน notebook ใช้ [MIT](LICENSE) ส่วนเนื้อหาอื่นทั้งหมด (ข้อความใน notebook, เว็บ และวิดีโอ) ใช้ [CC BY-NC-SA 4.0](LICENSE-CONTENT.md) ภาพหุ่น Microduck render จาก 3D model ของ Pollen Robotics (CC BY-NC-SA 4.0) รายละเอียดอยู่ใน [LICENSE-CONTENT.md](LICENSE-CONTENT.md)
