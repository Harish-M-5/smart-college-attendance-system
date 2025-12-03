# smart-college-attendance-system
An online attendance system that verifies student IP addresses to ensure secure and accurate attendance 

---

##📜 Introduction
This project is an **online attendance system** designed for college teachers. Students can mark their attendance **online** while ensuring authenticity using **IP address validation**. Only devices connected to the **college network** can mark attendance, preventing proxy or fake submissions from home. Attendance is recorded in a **Google Sheet** using Google App Script, so teachers do not need to manually mark attendance.  

**Key Idea:**  
- Students log in online and select their ID.  
- The system verifies the device’s **IP address** against allowed college IPs.  
- Attendance is recorded automatically in a **Google Sheet** via Google App Script.  
- Teachers can view attendance without manual work.  

---

## 📌 Explanation
1. **Student LSelection:** Students select their unique **Student ID** from a dropdown list.  
2. **IP Validation:** The system checks the **IP address** of the device. Only if it matches the **college network**, attendance is allowed.  
3. **Attendance Recording:** After validation, attendance is saved to a **Google Sheet** using **Google App Script**.  
4. **Status Feedback:** A success or error message is displayed after submission.  

## Flow:
`Student → Select ID → Verify IP → Attendance Saved in Google Sheet → Success Message`  

---

## 🧑‍💻Technology Used

| Technology | Purpose |
|------------|---------|
| **HTML** | Structure of the webpage |
| **CSS** | Styling, gradients, animations |
| **JavaScript** | Logic, IP check , attendance submission |
| **Google App Script** | Connect frontend to Google Sheets for recording attendance |

---

## ✨Features

- Online attendance marking from college devices  
- IP address verification to prevent fake attendance  
- Student-friendly dropdown for ID selection  
- Animated UI with smooth feedback messages  
- No manual teacher intervention needed  
- Attendance automatically recorded in **Google Sheets**  

---

##🛜 IP Address Details

| Type | IP Address |
|------|------------|
| **College IP** | 157.51.150.98 |
| **Student IP** | Automatically detected |

> Only if **student IP matches college IP**, attendance will be marked.  

---

## 🧻 Google Sheets Script Details

- A **Google App Script Web App** connects the frontend with Google Sheets.  
- Attendance is recorded with **Student ID, Timestamp, and IP Address**.  
- Example structure of Google Sheet:

| Student ID | Date & Time | IP Address |
|------------|-------------|------------|
| 1          | 03-12-2025 10:15 AM |157.51.150.98 |

- Google App Script listens to POST requests from the frontend and appends data to the sheet.

<img width="1920" height="1080" alt="Screenshot 2025-12-03 212444" src="https://github.com/user-attachments/assets/1bf85595-2f04-48f4-b064-d5b94634a7f1" />


<img width="1920" height="1080" alt="Screenshot 2025-12-03 212433" src="https://github.com/user-attachments/assets/9666b8a7-6a96-47f7-a6ee-d67e63345e74" />



Google App script URL 🖇️:
"https://script.google.com/macros/s/AKfycbyh_GT5cN9NZwJdJTMNVpYJS5o6GolChFx29HhSG3ld2eX-LT1sNcBbl_VsWaT-dp4Njw/exec";


---

## 🎛️ Git Setup

1. Clone the repository: 

git clone https://github.com/harish-m-5/smart-college-attendance.git

2. Navigate to project folder:

cd smart-college-attendance


3. Open in Browser

Open attendence student.html to see the system in action.

4. Commit changes:

git add .
git commit -m "Initial commit"
git push origin main

---

##🗒️ License

This project is MIT Licensed.
it are free to use, modify, and distribute it with proper credit.

---
## 📷 Ouput:

<img width="1920" height="1080" alt="Screenshot 2025-12-03 211050" src="https://github.com/user-attachments/assets/de9cf7ac-ac65-41a0-b4df-f591c74bf5ef" />

<img width="1920" height="1080" alt="Screenshot 2025-12-03 211036" src="https://github.com/user-attachments/assets/03e8924a-3e56-4546-979c-a3d7033d30ba" />

---

## 🎥 Demo Video


https://github.com/user-attachments/assets/62220dab-4c30-4d73-b382-d28f3fa63466






