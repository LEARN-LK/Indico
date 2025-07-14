#  How to Create and Manage a Conference in Indico

###  **Scenario:**

You are **Dr. ABC**, a lecturer at the University of Colombo, preparing to host the **National Research Conference 2025** on behalf of your faculty.

You’ve been granted permission by the LEARN Indico admin to organize a conference on the platform. Now, you want to:

* Create the event on Indico
* Set up abstract submissions and registration
* Assign speakers and sessions
* Manage participant interactions

Follow the steps below to complete your conference setup from start to finish.

---

###  A. Create a Conference

1. Go to your dashboard: `https://indico.learn.ac.lk`
2. Click **“Create event” [1]** → Choose **“Conference” [2]**
 <img src="https://github.com/LEARN-LK/Indico/blob/main/img/create-conference-01.png" width="430">
   
3. Fill in the basic details **[3]**:

   * **Title**: *National Research Conference 2025*
   * **Start/End Dates**: *August 20–22, 2025*
   * **Location**: *University of Colombo*
   * **Timezone**: `Asia/Colombo`
4. Click **Create Event [4]**

  <img src="https://github.com/LEARN-LK/Indico/blob/main/img/create-conference-02.png" width="430">

---

###  B. Configure Conference Basics

* Click on your name or profile icon at the top-right corner

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/conference-basic-01.png" width="430">
  
* Select **“My Profile [1]”** from the dropdown
* Under “your profile name”, find and click on the **event name [2]**
  Example: “National Research Conference 2025”

    
* On the conference page, click the ✏️ pencil icon (or Management button) to access the Management Area

  <img src="https://github.com/LEARN-LK/Indico/blob/main/img/conference-basic-02.png" width="530">

  <img src="https://github.com/LEARN-LK/Indico/blob/main/img/conference-basic-03.png" width="330">

* Under **Overview**:

  * Add a **banner/logo**
  * Set **description** of the event
    - You can use the following dummy data or add your own as you wish
      
| Field                    | Example Entry                                           |
| ------------------------ | ------------------------------------------------------- |
| **Title**                | National Research Conference 2025                       |
| **Description**          | A national platform to showcase university-led research |
| **Short URL**            | `nrc2025`                                               |
| **Date**                 | July 24–29, 2025                                        |
| **Time**                 | 8:30 AM – 3:30 PM                                       |
| **Timezone**             | Asia/Colombo                                            |
| **Venue**                | University of Colombo                                   |
| **Chairpersons**         | Dr. Nadeesha P, Prof. Ruwan A             |
| **Contact Title**        | Conference Coordinator                                  |
| **Contact Email**        | [nrc2025@learn.ac.lk](mailto:nrc2025@learn.ac.lk)       |
| **Phone**                | +94 11 2345678                                          |
| **Keywords**             | research, NRC 2025, academia, Sri Lanka                 |
| **Language**             | English                                                 |
| **Additional Languages** | Sinhala, Tamil                                          |
| **Map URL** (optional)   | Link to Google Maps                                     |
| **Additional Info**      | Please arrive 30 minutes early for on-site registration |


 * Choose **event visibility** (Public or Private)
---


##  C. Assign Organizers & Permissions.

>  **Important Note:**
> If you're working on a **brand-new Indico instance** or a fresh conference, the list of users will be **empty** at first. Users **must create their Indico accounts** (via Shibboleth or manual registration) **before you can assign them any permissions**.

###  Step-by-Step: Assigning Permissions to Users

1. **Ask other organizers or reviewers to first create an account:**

   * Either by:

     *  **Shibboleth login** (institution login via EduID)
     *  **Manual account registration**
   * Once they log in at least once, their account will exist in the system.

2. **Then go to your event [2] → Management Area [3] → Protection tab [4]**
<img src="https://github.com/LEARN-LK/Indico/blob/main/img/conference-basic-01.png" width="430">

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/conference-basic-02.png" width="530">
<img src="https://github.com/LEARN-LK/Indico/blob/main/img/Protection-01.png" width="40%">

   

3. Click **Add** → choose **User**

    <img src="https://github.com/LEARN-LK/Indico/blob/main/img/Protection-02.png" width="40%">

4. Type the name or email of the newly registered user

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/Protection-03.png" width="40%">
  
   * You will now be able to find and add them

5. Click the **pencil icon ✏️** next to the user’s name to assign specific roles/permissions:

   * Manage Abstracts
   * Registration
   * Surveys
   * Contributions
   * etc.

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/Protection-04.png" width="40%">
<img src="https://github.com/LEARN-LK/Indico/blob/main/img/Protection-05.png" width="20%">
6. Click **Save**

---

### Tip for Admins:

You can also **pre-register users** manually in the Indico Admin Panel (if you're a site admin), especially useful for:

* University staff
* Early invited speakers
* Key organizers

---





---

###  D. Build the Timetable

1. Go to **Timetable**
2. Click **“Add new session block”**
   Example: “Day 1 – Morning Session”
3. Add:

   * **Contributions** (e.g., “Keynote Address”, “Research Presentations”)
   * **Breaks**, **Lunch sessions**, etc.
4. Assign **speakers** and upload **slides** or other session materials

---

###  E. Enable Call for Abstracts

1. Go to **Call for Abstracts** → Click **Enable**
2. Set:

   * **Submission period**
   * **Tracks or topics** (e.g., Science, Technology, Humanities)
   * **Abstract format** (text box, file upload)
3. Add **reviewers** to assess submissions
4. Define **acceptance criteria**

---

###  F. Create a Registration Form

1. Go to **Registration** → Click **“Create a new form”**
2. Set:

   * **Registration title** (e.g., “NRC 2025 Registration”)
   * **Open/Close dates**
   * **Maximum number of participants**
3. Add form fields:

   * Name, Email, Affiliation
   * Presenter status (yes/no)
   * Dietary or accessibility needs
4. Save and **Enable the form**

---

###  G. Enable Payments (Optional)

1. Go to the **Payments** tab
2. Enable:

   * **Offline payments** (e.g., bank deposit)
   * **Online** options like Stripe or PayPal (if configured)
3. Set **pricing tiers** for students, staff, and external participants

---

###  H. Add Rooms & Venues

1. Go to **Rooms**
2. Add:

   * Room name (e.g., “Main Auditorium”)
   * Seating capacity
   * Available equipment (Projector, Microphones, Wi-Fi)
3. Assign rooms to session blocks in your **Timetable**

---

###  I. Promote the Conference

* Make the event **Public** (if open to external attendees)
* Share the event link:
   `https://indico.learn.ac.lk/event/1`
* Enable:

  * **Calendar export (.ics)**
  * **Email updates** to attendees

---

###  J. Monitor & Manage the Event

* Review:

  * **Registrations** → Export participant list to Excel
  * **Abstract status** → Accept or reject submissions
  * **Speaker materials** → Slides, papers, and media uploads
* Send:

  * Confirmation emails
  * Session reminders

---

###  K. End and Archive the Conference

* Close:

  * **Abstract submission**
  * **Registration**
* Upload final materials to **Materials** tab
* Generate and distribute:

  * **Certificates** (if plugin enabled)
  * **Feedback forms**
* Change visibility to **Archived**

---
