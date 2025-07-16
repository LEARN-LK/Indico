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

6. Click**Save**

---

### Tip for Admins:

You can also **pre-register users** manually in the Indico Admin Panel (if you're a site admin), especially useful for:

* University staff
* Early invited speakers
* Key organizers

---


##  D. Build the Timetable

The **Timetable** is the heart of your Indico conference. It allows you to define and organize the full event structure—sessions, presentations, breaks, and speaker slots.

---

###  Step-by-Step: Build the Timetable

1. **Go to your Event** → Click **Management Area**
2. Navigate to the **Timetable  [1]** tab

 <img src="https://github.com/LEARN-LK/Indico/blob/main/img/timetable-1.png" width="230">

   
3. Click **Add new session block [2]**

   * Enter:

     * **Title**: e.g., “Opening Ceremony”
     * **Date & Time**: e.g., **July 24, 2025, 08:30 AM**
     * **Location**: Main Auditorium
   * Click **Create**

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/timetable-2.png" width="530">
<img src="https://github.com/LEARN-LK/Indico/blob/main/img/timetable-addnewsession-3.png" width="530">

4. Inside that session block, click **Add contribution [3]**

   * Fill in:

     * **Title**: e.g., “Welcome Speech”
     * **Speaker**: e.g., Prof. Ruwan Abeysekera
     * **Duration**: e.g., 30 minutes
     * Conveners: If not available, you can:
       - Add Myselfe
       - Add from Search
       - Enter Manually
   * Click **Create**

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/timetable-addnewsession-4.png" width="530">
     
5. Repeat for all sessions, talks, and panels
6. Optionally, upload slides or materials for each contribution

---

###  Example: National Research Conference 2025

| **Date**      | **Time**      | **Session Block**       | **Contribution**         | **Speaker**            | **Location**    |
| ------------- | ------------- | ----------------------- | ------------------------ | ---------------------- | --------------- |
| July 24, 2025 | 08:30 – 09:30 | Opening Ceremony        | Welcome Speech           | Prof. Ruwan Abeysekera | Main Auditorium |
| July 24, 2025 | 09:30 – 10:30 | Keynote Session 1       | Future of AI in Research | Dr. Anoma Perera       | Main Auditorium |
| July 24, 2025 | 11:00 – 13:00 | Parallel Track: Science | 4 Paper Presentations    | Various Authors        | Hall A          |
| July 24, 2025 | 13:00 – 13:30 | Break                   | Lunch Break              | —                      | Cafeteria       |
| July 24, 2025 | 13:30 – 15:30 | Parallel Track: Tech    | 5 Paper Presentations    | Various Authors        | Hall B          |

---

###  Materials

* Upload presentations, research papers, or session videos:

  * Go to the contribution → Click **Materials**
  * Click **Upload files**

---

###  Speaker & Chair Management

* Add multiple speakers if needed
* Assign **Session Chair** during session creation or editing
* Indicate time allocation and breaks clearly


---

###  E. Enable Call for Abstracts

Once you’re inside your event:

>  Go to **Management Area** → **Call for Abstracts [1]** → **Click the gear icon [2] ⚙️**


<img src="https://github.com/LEARN-LK/Indico/blob/main/img/abstract-01.png" width="230">
<img src="https://github.com/LEARN-LK/Indico/blob/main/img/abstract-02.png" width="430">

Then you'll see the screen you uploaded. Here's how to configure it:

---

###  **Announcement [3]**


<img src="https://github.com/LEARN-LK/Indico/blob/main/img/abstract-03.png" width="630">

* Add a message here for all potential abstract submitters.
*  Example:

  ```
  We welcome abstracts related to Science, Technology, and Humanities for NRC 2025. Please ensure your submission is original and aligns with our tracks.
  ```

---

###  Submission Options

| Setting                   | Recommendation for NRC 2025                         |
| ------------------------- | --------------------------------------------------- |
| **Multiple tracks**       |  ON – Allow choosing from multiple research tracks |
| **Require tracks**        |  ON – Must pick a track (Science/Tech/Humanities)  |
| **Require contrib. type** |  OFF (Optional – only enable if you use types)     |
| **Allow attachments**     |  ON – Allow upload of files (PDF, DOC)             |
| **Allow speakers**        |  ON – Allow submitters to tag a speaker            |
| **Require a speaker**     |  ON – Force them to pick at least one speaker      |

---

###  **Allow Editing [4]**

Choose who can edit the abstract after submission:

* Recommended: **All involved people (submitter, authors, speakers)**

---

###  **Contribution Submitters [5]**

Who can submit contributions *after* abstract is accepted:

* Recommended: **Speakers, authors, and co-authors**

---

###  **Authorized Submitters [6]** (Optional)

This allows **specific users** to bypass the regular submission deadline.

 Example:

* Add committee members who need to upload late abstracts
* Click **Add** → choose User/Group/Event Role

---

###  **Instructions [7]**

This appears right before the submission form.

 Example:

```
1. Submit your abstract before July 15, 2025.
2. Use formal academic language and keep it under 300 words.
3. Upload supporting documents (if required).
4. Select the appropriate track (Science, Tech, Humanities).
```

---

###  Final Step

Click **Save [8]** at the bottom once you're done.

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
