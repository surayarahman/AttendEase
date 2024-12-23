## Group Name
Midgardians

## Group Member Details
- **Name:** SURAYA RAHMAN ERIN **Matric No:** 2114128
- **Name:** MUHAMMAD ZUBAIR IMRAN BIN MD ASRI **Matric No:** 2126487
- **Name:** MUHAMMAD FAYYADH KHUMAINI BIN KHAMSANI **Matric No:** 2112233

## Tasks Assigned to Group Members
- **SURAYA RAHMAN ERIN:** Responsible for writing the project initiation (App proposal, purposes or objectives, features, target user, platform and background) and setting up the repository.
- **MUHAMMAD ZUBAIR IMRAN BIN MD ASRI:** Responsible for providing a sequence diagram, and screen navigation flow as your logical design.
- **MUHAMMAD FAYYADH KHUMAINI BIN KHAMSANI:** Responsible for evaluate technical feasibility and back-end assessments such as data storage for CRUD operations, packages, and plugins. Ensure compatibility of the app with the chosen platform (smartphones and wearables).

# AttendEase Development Plan

## PROJECT INITIATION
### 1. Title
- **AttendEase**
A mobile application that records classroom attendance using camera scanning.

### 2. Background of the Problem
- Tracking student attendance in educational institutions has traditionally been a manual process, often leading to inaccuracies, especially in large classrooms. Instructors struggle to maintain accurate records, and methods like attendance sheets are prone to errors, misplacements, and fraud. These practices waste valuable class time and are vulnerable to human error.

- As technology increasingly integrates into education, traditional attendance tracking methods have become inefficient and outdated. The need for faster, more accurate, and reliable attendance monitoring is critical as educational institutions evolve. Moreover, in unforeseen circumstances like the COVID-19 pandemic, where social distancing and hybrid learning are necessary, a technological solution for tracking attendance is not just beneficial but essential.

### 3. Purpose or Objective
The purpose of AttendEase is to automate student attendance through advanced facial recognition technology. By utilizing mobile device cameras and cutting-edge machine learning, the application accurately identifies students and marks their attendance in real time, eliminating the need for physical intervention.

**Objectives:**

- To offer a quick and efficient attendance solution that minimizes human error and saves valuable class time.
- To ensure data accuracy with real-time updates to attendance records accessible to both instructors and students.
- To enhance security and student engagement through advanced facial recognition.

By automating attendance tracking, AttendEase aims to improve the educational experience by streamlining the process and removing the challenges of manual checks.

### 4. Target User
The target users for AttendEase is both students and instructors in academic institutions, specifically:

**i. Teachers/Professors/Instructors:**
They can use the app for automated attendance marking during lectures, ensuring accurate and secure data without manual checks.

**ii. Students:** 
They will benefit from the automated process, receiving instant feedback on their attendance status and reducing the risk of unjustified absences.

**iii. Administrators:** 
Educational institutions can track overall attendance data and trends to provide reports or assessments regarding student participation, leading to better decision-making.
The app’s primary focus will be on higher education classrooms with a considerable number of students, where face recognition technology will significantly reduce the administrative worload.

### 5. Preferred Platform
The app will be developed for both Android and iOS using Flutter to ensure wide accessibility across the most commonly used devices.

With the growing number of mobile users, a cross-platform app guarantees availability on both Android and iOS. This mobile-first approach will deliver an intuitive, user-friendly experience without the need for extra hardware or complex installations.

### 6. Features and Functionalities
**Camera-based Attendance Marking:**
The main feature will allow instructors to scan the classroom or students using their mobile device's camera. The app will recognize faces and mark the attendance automatically.

**Real-time Attendance Update:**
After scanning the classroom, attendance will be updated in real-time to a cloud-based system, which can be accessed by both instructors and students.

**Classroom Management Dashboard:**
Instructors will be able to manage their classes by viewing the list of enrolled students, attendance records, and trends over time.

**Attendance Report Generation:**
Instructors will have the option to generate attendance reports in formats like PDF or Excel for submission or records.

**Notifications for Students:**
If a student is marked absent or late, they will receive a notification to keep track of their attendance status.

**Security Features:**
A password-protected system for instructor login to ensure that only authorized users have access to sensitive data.

## Understanding the need for AttendEase
Why this mobile app is necessary:

**Efficiency:** Automating attendance with a user-friendly app saves valuable teaching time, allowing instructors to concentrate on educating while providing students with real-time attendance feedback.

**Accuracy:** Face recognition technology ensures precise attendance tracking, eliminating issues related to mistaken identity or human error.

**Convenience:** Instructors and students enjoy accessible, real-time attendance updates on their mobile devices, promoting transparency and accountability.

## How we arrived at the idea:
**Research and observations**
Recent studies have revealed that the traditional method of taking attendance in classrooms is often monotonous, time-consuming, and inefficient. This can waste valuable instructional time and negatively affect the educational experience for both teachers and students. To address this problem, we thoroughly investigated the use of mobile technology, focusing on innovations such as facial recognition systems and advanced camera features. Our research resulted in the development of AttendEase, a modern tech solution designed to improve time management and enhance the accuracy of attendance records. 

**Development potential:**
As the demand for innovative technology in education grows, AttendEase emerges as a fitting solution that aligns with the trend of digitizing classrooms and modernizing educational practices. By streamlining the attendance process, AttendEase saves time and fosters a more organized and efficient learning environment.

## REQUIREMENT ANALYSIS
**1.Technical Feasibility and Back-End Assessments**
    **a.Data Storage for CRUD Operations**
        **Database Selection:** Use Cloud Storage for Firebase (Firebase Firestore).
    **b.CRUD Operations Design:**
        **Create:** Add student records, attendance logs, and face recognition data.
        **Read:** Fetch attendance logs, student details.
        **Update:** Edit attendance records, and facial recognition details.
        **Delete:** Remove records when necessary (e.g., old attendance logs or incorrect data).

**2. Ensure Compatibility with Platforms**
     **a. Smartphones (Android & iOS):**
            -Use Flutter for cross-platform development.
            -Ensure app performance in both Android and iOS versions.
        
## DIAGRAMS
**Sequence Diagram**

![Sequence diagram (3)](https://github.com/user-attachments/assets/a19a1e9a-e5a8-4e1c-93e4-926c5638e5e5)

**Screen Navigation Flow**

![Blank diagram (5)](https://github.com/user-attachments/assets/55bd1d5f-6868-44d6-aae0-067aefde52f9)

## GANTT CHART
![AttendEase Gantt Chart-1](https://github.com/user-attachments/assets/d3b1cdea-28f3-4ceb-a47a-f6b6e0634c50)

## REFERENCES

Kumara, P. M., Tahmasebi, M., & Sethu, D. (2021). Automatic attendance recording system using facial recognition. Malaysian Journal of Science, Advanced Technology, 1(2), 68–71. https://mjsat.com.my/index.php/mjsat/article/view/12

Gaffar, A. (2024). The facial recognition technology in academic attendance. International Journal of Technology and Innovative Management, 1(1), 103–120. https://journals.gaftim.com/index.php/ijtim/article/view/363
