## Part 3: I – Setup Email Notifications

This step helps you configure **automated email notifications** for your Indico conference (e.g., National Research Conference 2025) to keep participants and organizers informed at every stage.

---

### Step-by-Step Tasks

### **Step 1: Configure Registration Notifications**
**Location**: Management Area → Registration → Configure
1. Go to the **Management Area** of your event (e.g., National Research Conference 2025).
2. Click **Registration [1]** in the left menu, then select **Manage [2]** in "NRC 2025 Participant Registration" form.

   <img src="https://github.com/LEARN-LK/Indico/blob/main/img/reg-email-notification-01.png" width="430">
3. Then Click on **General Settings** and Click on **EDIT [3]**

   <img src="https://github.com/LEARN-LK/Indico/blob/main/img/reg-email-notification-02.png" width="430">
   
4. In the **Notifications for registrants** section:

   <img src="https://github.com/LEARN-LK/Indico/blob/main/img/reg-email-notification-03.png" width="430">
   
   - Set the **Notification sender** email address (e.g., `noreply@learn.ac.lk`). If empty, the default Indico email is used.
   - Customize the **Message for pending registrations [4]** (sent to users like Suresh awaiting approval). Use Markdown syntax and placeholders like `{registrant_full_name}` or `{event_name}`.
   - Customize the **Message for unpaid registrations [5]** (sent if a fee is set).
   - Customize the **Message for complete registrations[6]** (sent upon approval and payment, if applicable).
   - Check **Attach iCalendar file** to include a calendar invite with complete registration emails.
6. In the **Notifications for organizers [7]** section:
   - Check **Enabled** to send organizers email notifications about new registrations (e.g., when Gayan Bandara’s registration was submitted).
7. Ensure **Moderated** is checked under the registration form settings to enable the pending approval process.
8. Save changes by clicking **Save**.

### **Step 2: Manage Registrations and Trigger Notifications**
**Location**: Management Area → Registration → Registrants
1. Go to **Registration** in the Management Area, then select **Registrants** to view the list of registrations.
2. Locate the pending registration (e.g., Gayan Bandara, ID #2, submitted Jul 29, 2025, 02:20 PM).
3. Use the **Moderation** dropdown to:
   - **Approve registrations**: Sends the "Message for complete registrations" to the registrant (e.g., `gayan@learn.ac.lk`) and, if enabled, to organizers.
   - **Reject registrations**: Sends a rejection notification (if configured in the template).
   - **Reset registrations**: Resets the registration state, potentially triggering a follow-up email.

### **Step 3: Set Up Abstract Submission Notifications**
**Location**: Management Area → Call for Abstracts → Reviewing → Notification Templates
1. Go to **Call for Abstracts** in the Management Area.
2. Click the **Reviewing** tab, then select **Notification Templates**.
3. Click **Add** to create a new template:
   - **Title**: E.g., "Abstract Accepted."
   - **From Address**: Set the sender email.
   - **To Address**: Select recipients (e.g., submitters, primary authors).
   - **Condition**: Choose when the email is sent (e.g., abstract accepted, rejected).
   - Use placeholders like `{abstract_title}`, `{submitter_full_name}`, or `{event_name}`.
4. Save the template. Emails will be sent automatically when conditions are met.

#### **Step 4: Send Manual Emails (Optional)**
**Location**: Management Area → Registration → Registrants → Email
1. Go to **Registration → Registrants → Email**.
2. Select recipients (e.g., all registrants, including Gayan Bandara, or specific groups like presenters).
3. Compose the email, attaching files or links as needed, and use placeholders for personalization.
4. Send the email to notify participants manually.

---

### Example Scenario
For **National Research Conference 2025** (held 18 Aug - 20 Aug 2025):
- **Pending Registration Notification** (sent to `gayan@learn.ac.lk`):
  > *Subject: NRC 2025 – Registration Pending*  
  > *Dear {registrant_full_name},*  
  > *Your registration for the National Research Conference 2025 (18–20 Aug 2025) is pending approval. We will notify you once reviewed...*
- **Registration Approval** (after approving Gayan Bandara’s registration):
  > *Subject: NRC 2025 – Registration Approved*  
  > *Dear {registrant_full_name},*  
  > *Your registration for the National Research Conference 2025 is approved. Event details: 18–20 Aug 2025...*

---

### Notes
- **Moderation**: The "Pending" state for Gayan Bandara’s registration (Jul 29, 2025, 02:20 PM) confirms moderation is active. Approve or reject it to trigger the respective notifications.
- **Placeholders**: Verify available placeholders in the template editor (e.g., `{registrant_full_name}`, `{event_name}`).
- **Testing**: Test notifications by approving/rejecting a test registration (e.g., your own) and checking the email sent to `gayan@learn.ac.lk`.
- **Time Sensitivity**: Act on pending registrations promptly, as the event is scheduled for 18–20 Aug 2025.
- **Support**: Refer to Indico v3.3.7 documentation or contact support for template customization help.

---

This updated guide integrates the registration configuration and moderation process, ensuring email notifications are set up and triggered correctly for the "National Research Conference 2025." Let me know if you need assistance with specific actions (e.g., approving Gayan Bandara’s registration) or further customization!
