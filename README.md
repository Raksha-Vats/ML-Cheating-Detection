# Cheating Detection for ASU Classroom

### 🔎 Overview

This project presents a Computer Vision (CV) based solution designed to enhance cheating detection during exams in classroom settings at Rajiv Gandhi Institute of Petroleum Technology (RGIPT). By leveraging CV technology to monitor students' head and eye movements, the solution aims to ensure academic integrity, promote honesty, and encourage the development of fair study habits.

---

### 📝 Problem Definition

Maintaining academic integrity during exams is a persistent challenge in educational institutions. Traditional surveillance methods may fail to detect **covert cheating behaviours**, such as secret interactions between students or sneaking glances at unauthorised materials. This project seeks to address these gaps using **computer vision technology**.

---

### 💡 Importance of the Solution

Implementing a real-time monitoring system using CV can help in:
- **Enhanced cheating detection**: Monitoring student behavior more effectively.
- **Fostering a culture of honesty**: Building trust between students and faculty.
- **Promoting integrity**: Encouraging students to focus on fair study habits and avoid malpractices.

---

### 👥 Stakeholders and Beneficiaries

- **Stakeholders**: Faculty members, Office of Academic Integrity, Information Technology Department.
- **Beneficiaries**: Students and the academic community benefiting from fair assessments.
---

### ⚙️ Current Solutions and Limitations

Current solutions like browser lockdowns and seating arrangements cannot detect **subtle behavioural indicators** of cheating, such as:
- Sneaking glances at unauthorised materials.
- Secret interactions between students.
- Lack of live feedback for proctors during the exam.

---

### 💻 Proposed Solution (Role of Computer Vision)

Our proposed solution uses **CV algorithms** to track and analyse students' head and eye movements in real-time during exams. This system identifies suspicious behaviour such as:
- Continuously looking away from the front view.
- Glancing in directions unrelated to the exam task.

The system employs **high-resolution webcams** to capture data, which is processed in real-time to detect and flag potential cheating patterns.

---

### 🔄 E2E Product Workflow

1. **Real-Time Monitoring**: Captures students' head and eye movements.
2. **Immediate Analysis**: CV model analyses live feed for cheating indicators.
3. **Live Alerts**: Sends alerts when potential cheating is detected.
4. **Intervention Protocol**: Proctors are alerted to take real-time action.
5. **Confirmation & Action**: Proctors confirm and act on the identified cheating cases.

---

### 📊 Models Used

1. **YOLOv4 - Object Detection**
   - Detects human figures and objects such as phones or notes in real time.
   - Tracks the presence and location of unauthorised materials.



2. **Shape_Predictor_68_Face_Landmarks - Face Detection**
   - Monitors **eye movement direction** and **head orientation** to detect cheating behavior.

<img src="multiple.png" align="center" width="576" height="360" style="margin-top: 40px;">
   
<img src="one.png" align="center" width="576" height="360" style="margin-top: 40px;">
   
<img src="phone.png" align="center" width="576" height="360" style="margin-top: 40px;">

---

### ⚠️ Possible Limitations/Risks

- **Narrow Object Detection**: Limited object recognition capabilities.
- **Limited Accuracy**: Potential operational errors in identifying cheating behaviour.
- **Device Usage Limitation**: Limitations on compatible devices and hardware.


---

### 🔗 Links:
- Dataset:
- Report:
- Presentation: https://tinyurl.com/dxhces2x

