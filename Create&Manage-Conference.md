#  University Manager Task: Create Conference & Configure Features
Once the university coordinator (e.g., Dr. Silva) is added as a manager, they can proceed with full conference setup.

---

###  A. Create a Conference

1. Log in as Dr. Silva
2. Navigate to University of Peradeniya category
3. Click **“Create event” [1]** → Choose **“Conference” [2]**
 <img src="https://github.com/LEARN-LK/Indico/blob/main/img/create-conference-01.png" width="430">
 
4. Fill in the basic details **[3]**:

   * **Title**: *National Research Conference 2025*
   * **Start/End Dates**: *August 20–22, 2025*
   * **Location**: *University of Colombo*
   * **Timezone**: `Asia/Colombo`
5. Click **Create Event [4]**

  <img src="https://github.com/LEARN-LK/Indico/blob/main/img/create-conference-02.png" width="430">

---

###  B. Configure Conference Basics

* Click on your name or profile icon at the top-right corner

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/conference-basic-01.png" width="430">
  
* Select **“My Profile [1]”** from the dropdown
* Under “your profile name”, find and click on the **event name [2]**
  Example: “National Research Conference 2025”

    
* On the conference page, click the  pencil icon (or Management button) to access the Management Area

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


##  Step F: Create a Registration Form

###  Purpose:

Collect participant details, manage attendance, and optionally enable payment.

---

###  **Step-by-Step Guide**

### **1. Navigate to Registration Module**

Go to your event → Management Area → **Registration [1]**

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/registration-form-01.png" width="230">

---

### **2. Click "Create a New Registration Form [2]"**

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/registration-form-02.png" width="630">


You'll see the screen just like your screenshot.

#### ⚙️ Initial Settings:

| Field                          | Description                               | Example                                      |
| ------------------------------ | ----------------------------------------- | -------------------------------------------- |
| **Title [3]**                      | Name of the form                          | NRC 2025 Participant Registration            |
| **Visibility to participants [4]** | Who can see the participant list          |  Recommended: *Hide all participants*       |
| **Visibility to everyone [5]**     | Whether non-participants can see the list |  Recommended: *Hide all participants*       |
| **Visibility duration [6]**        | How long the list is visible              | Leave as default (Permanent or adjust later) |
| **Retention period [7]**           | How long data is stored                   | Optional (set to 4–12 weeks or indefinite)   |

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/registration-form-03.png" width="630">

 Click **Create [8]** to continue.

---

### **3. Design the Form**

Once the form is created, Then select **Registration Form Configure [9]** settings.

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/registration-form-04.png" width="630">

#### ➕ Add Form Fields:

* **Name** *(required)*
* **Email**
* **Affiliation / University**
* **Presenter?** *(Yes/No radio button)*
* **Mobile Number**
* **Dietary/Accessibility Requirements**
* **Upload Student/Staff ID** *(if needed)*

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/registration-form-05.png" width="630">

---

### **4. Set Form Settings**

Click the **Start now or schedule opening** in the registration form:

| Option                     | Example Configuration                |
| -------------------------- | ------------------------------------ |
| **Registration opens**     | Jul 1, 2025                          |
| **Registration closes**    | Jul 23, 2025                         |
<!--| **Max participants**       | 300                                  |
| **Moderated registration** | Enabled if manual approval is needed | -->

<img src="https://github.com/LEARN-LK/Indico/blob/main/img/registration-form-06.png" width="630">
---

### **5. Enable and Share**

After designing and configuring:

* Click **Enable Registration**
* Share the registration link with your participants

 Link will be like:
`https://indico.learn.ac.lk/event/1/registration/1/`

---

###  G. Enable Payments (Optional)

1. Go to the **Payments** tab
2. Enable:

   * **Offline payments** (e.g., bank deposit)
   * **Online** options like Stripe or PayPal (if configured)
3. Set **pricing tiers** for students, staff, and external participants

---

###  H. Add Rooms & Venues

###  Purpose:

Define the physical or virtual locations where your sessions will take place and link them to session blocks in the timetable.

---

###  **Step-by-Step Guide**

### **1. Navigate to the Rooms Module**

1. **Open your Event**
   Go to your event (e.g., *National Research Conference 2025*)

2. **Enter Management Area**
   Click the **gear icon** at the top right of the page to open the **Management Area**

3. **Go to "Rooms" Module**
   In the left-hand sidebar, scroll down to the **“Reports”** section
   Click on **“Rooms”**

4. **Click "Add Room"**

---

###  Here's how to handle this situation:

#### 🛠️ Option 1: Use the **Venue/Room fields** in the Event Settings

Even if the **Rooms module** is not visible, you can still **manually add the venue and room name** in the event’s **main Settings section**:

---

###  **Update Venue & Room in Event Settings (Manual Entry)**

1. Go to your Event (e.g., *National Research Conference 2025*)
2. Click the **gear icon** (Management area)
3. Under the **Settings** tab:
4. Click the **pencil icon** next to the **Room** field 
 
---

### **2. Add a New Room**

Click **“Add Room”** or **“+ New Room”**, then fill in the details:

####  Example Room Configuration:

| Field                             | Value                                   |
| --------------------------------- | --------------------------------------- |
| **Room Name**                     | Main Auditorium                         |
| **Site**                          | University of Colombo                   |
| **Building**                      | Faculty of Science Block A              |
| **Floor**                         | Ground                                  |
| **Room Number**                   | 101                                     |
| **Capacity**                      | 300                                     |
| **Available Equipment**           |  Projector<br> Microphones<br> Wi-Fi |
| **Location Map URL** *(optional)* | \[Add Google Maps or image link]        |

Click **Save** once all details are added.

 Repeat this step for all rooms (e.g., Seminar Room A, Online Zoom Room, Workshop Lab 1).

---

### **3. Assign Rooms to Session Blocks in the Timetable**

To associate rooms with your scheduled sessions:

#### Steps:

1. Go to your event → **Timetable**
2. Click on the **session block** you want to assign a room to
3. Click the **Edit** (pencil) icon
4. Choose the room from the **Location** dropdown
5. Save

#### Example:

* **Session:** Research Presentations – Day 1
* **Time:** 9:00 AM – 12:00 PM
* **Room:** Main Auditorium

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
