# ASTRA+ ✨ – Your Universe of Knowledge and Mentorship!

**ASTRA+** is not just a platform; it's your trusted guide in the world of education, connecting inquisitive students with talented teachers. We strive to make learning accessible, convenient, and effective for everyone. Find your ideal tutor or share your knowledge with the world!

---

## 🚀 About ASTRA+

In today's dynamic world, quality education and a personalized approach to learning are key to success. ASTRA+ was created to meet this demand by providing an innovative online platform where students can easily find qualified teachers in any subject, and teachers get the opportunity to share their expertise and expand their practice.

Our mission is to ignite the stars of knowledge in everyone!

---

## 🌟 Key Features of the ASTRA+ Platform

ASTRA+ offers a wide range of features designed to ensure comfortable and productive interaction between all participants in the educational process.

### 🎓 For Students:

* **Easy Teacher Search:**
    * Find the perfect tutor by subjects, categories (preschoolers, schoolchildren, adults), teaching languages, city (for offline lessons), and price.
    * Detailed public teacher profiles with information about experience, education, methodologies, and reviews.
* **Convenient Lesson Booking:**
    * View teacher availability on their interactive schedule.
    * Book lessons online in just a few clicks.
* **Effective Learning:**
    * Receive links for online lessons (e.g., Google Meet).
    * Access homework and notes from the teacher.
* **Transparency and Feedback:**
    * Leave ratings and reviews after completed lessons, helping other students make their choice.
    * View your lesson history and payments.
* **Personalized Dashboard:**
    * Manage your profile, view scheduled and past lessons.
    * Receive internal notifications about lesson confirmations, cancellations, and new homework.
* **Security and Control:**
    * Secure registration system with email activation.
    * Ability to change and recover your password.

### 👨‍🏫 For Teachers:

* **Create a Professional Profile:**
    * Provide detailed information about yourself: name, age, photo, contact details.
    * Specify the subjects you teach, student categories, languages, work experience, education, and lesson price.
    * Share information about your teaching approach and hobbies.
    * Add links to social media (Telegram, Instagram, etc.).
* **Flexible Schedule Management:**
    * Create and edit your availability schedule, indicating days of the week and time slots.
    * The system automatically prevents lesson overlaps.
* **Efficient Lesson Management:**
    * Confirm lesson requests from students.
    * Create lessons for your students.
    * Add links to video conferences, homework, and private notes to lessons.
    * Mark lessons as completed and paid.
    * Ability to cancel lessons, notifying the student.
* **Interaction with Students:**
    * View a list of your students.
    * Receive notifications about new bookings, cancellations, and reviews.
* **Transparency and Reputation:**
    * Receive ratings and reviews from students (after moderation).
    * "Verified Teacher" status to increase trust (assigned by an administrator).
* **Personalized Dashboard:**
    * Manage your profile, schedule, and lessons.
    * Secure password change and recovery.

### ⚙️ General Platform Features:

* **Clear User Roles:** Student, Teacher, Administrator.
* **Secure Authentication:** Login with email and password using JWT (JSON Web Tokens - access and refresh).
* **Notification System:** Internal messages for users about important events.
* **Public Directories:** Lists of cities, subjects, languages, and student categories for easy searching and filtering.
* **Admin Panel:** Tools for administrators to manage users, teacher profiles (verification), moderate reviews, and general platform monitoring.

---

## 🛠 Technology Stack (Briefly)

* **Backend:** Django, Django REST framework
* **Database:** PostgreSQL (or other Django-supported relational DB)
* **Authentication:** JWT (JSON Web Tokens)

---

## 🗺️ API Endpoint Overview (High-Level)

ASTRA+ provides an extensive RESTful API for interacting with the platform.

* **User Endpoints (`/api/user/`):**
    * Registration, account activation.
    * Login, token refresh.
    * Password change/reset.
    * Management of student and teacher profiles (`/me/`).
    * Public list and details of teachers.
    * Directories (cities, subjects, languages, categories).
* **Teaching Endpoints (`/api/teaching/`):**
    * Teacher schedule management.
    * Lesson creation, retrieval, update, cancellation.
    * Rating creation and retrieval.
    * Notification retrieval and status update.
    * Public teacher availability.
    * List of students for a teacher.

---

## 🚀 Getting Started (For Users)

1.  **Sign Up:** Create an account by choosing the Student or Teacher role.
2.  **Activate:** Confirm your email address by clicking the link in the activation email.
3.  **Students:** Start searching for teachers, view profiles, and book lessons!
4.  **Teachers:** Complete your detailed profile, specify your subjects, experience, and set up your schedule. Wait for student requests or add lessons yourself!

---

Thank you for choosing **ASTRA+** – your journey to new knowledge begins here! 🌠
