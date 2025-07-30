## I – Setup Email Notifications

This step helps you configure **automated email notifications** for your Indico conference (e.g., National Research Conference 2025) to keep participants and organizers informed at every stage.

---

## 1: Configure Registration Notifications**
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

## 2: Manage Registrations and Trigger Notifications**
**Location**: Management Area → Registration **[1]**]* → Registrants
1. Go to **Registration [1]** in the Management Area, then select **Registrants [2]** to view the list of registrations.

    <img src="https://github.com/LEARN-LK/Indico/blob/main/img/reg-approve-01.png" width="430">
2. Locate the pending registration **[3]**(e.g., Gayan Bandara, ID #2, submitted Jul 29, 2025, 02:20 PM).
3. Use the **Moderation [4]** dropdown to:

   <img src="https://github.com/LEARN-LK/Indico/blob/main/img/reg-approve-02.png" width="430">
   
   - **Approve registrations**: Sends the "Message for complete registrations" to the registrant (e.g., `gayan@learn.ac.lk`) and, if enabled, to organizers.
   - **Reject registrations**: Sends a rejection notification (if configured in the template).
   - **Reset registrations**: Resets the registration state, potentially triggering a follow-up email.

---

### 3: Set Up Abstract Submission Notifications
**Location**: Management Area → Call for Abstracts → Submission → Notifications
1. Ensure the "Call for Abstracts" feature is enabled:
   - Go to **Management Area → Call for Abstracts → Setup** and confirm it is active (as shown in the second screenshot with "The call for abstracts is open").
2. Go to **Call for Abstracts** in the Management Area.
3. Click the **Submission** tab at the top of the Call for Abstracts section.
4. Click the **Notifications** button (envelope icon) to open the "Configure e-mail notifications" panel (as shown in the first screenshot).
5. Configure the notification templates:
   - Locate the desired template (e.g., "Submitted," "Accepted," "Rejected," etc.).
   - Click **Edit** (pencil icon) for the template you want to modify.
   - Set the **From Address** (e.g., `noreply@learn.ac.lk`) if not preconfigured.
   - Customize the email content using placeholders like `{abstract_title}`, `{submitter_full_name}`, or `{event_name}` (verify available placeholders in the editor).
   - The condition is predefined based on the template’s state (e.g., "Accepted" triggers when an abstract is accepted).
6. Click **Save** to store the template. Emails will be sent automatically when the abstract reaches the corresponding state (e.g., after acceptance).
7. (Optional) Reorder the list of notifications or enable "stop on match" to control notification priority, as noted in the interface.

---



## 4: Send Manual Emails (Optional)**
**Location**: Management Area → Registration → Registrants → Email **or** Call for Abstracts → List of Abstracts → Email **or** Participants → Email
1. For registrants:
   - Go to **Registration → Registrants → Email**.
   - Select recipients (e.g., all registrants including Gayan Bandara, or specific groups like presenters).
2. For abstract authors/reviewers:
   - Go to **Call for Abstracts → List of Abstracts → Email**.
   - Select specific abstracts and choose recipients (e.g., authors or reviewers).
3. For meeting participants:
   - Go to **Participants → Email**.
   - Select participants to email.
4. Compose the email, attaching files or links as needed, and use placeholders (e.g., `{registrant_full_name}`, `{abstract_title}`) for personalization.
5. Click **Send** to deliver the email immediately to the selected recipients.

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
- **Abstract Acceptance** (sent to a submitter):
  > *Subject: NRC 2025 – Abstract Accepted*  
  > *Dear {submitter_full_name},*  
  > *Your abstract titled "{abstract_title}" has been accepted for Session 3 on Aug 19.*

---

