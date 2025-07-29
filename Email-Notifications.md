
## Part 3: I – Setup Email Notifications

This step helps you configure **automated email notifications** for your Indico conference (e.g., National Research Conference 2025) to keep participants, reviewers, and organizers informed at every stage.

---

### Step-by-Step Tasks

#### **Step 1: Configure Registration Notifications**
**Location**: Management Area → Registration → Configure
1. Go to the **Management Area** of your event (e.g., National Research Conference 2025).
2. Click **Registration** in the left menu, then select **Configure** next to the "IRC Registration" form.
3. In the **Notifications for registrants** section:
   - Set the **Notification sender** email address (e.g., `noreply@learn.ac.lk`). If empty, the default Indico email is used.
   - Customize the **Message for pending registrations** (sent to users awaiting approval if moderation is enabled). Use Markdown syntax and placeholders like `{registrant_full_name}` or `{event_name}`.
   - Customize the **Message for unpaid registrations** (sent if a registration fee is set).
   - Customize the **Message for complete registrations** (sent upon approval and payment, if applicable).
   - Check **Attach iCalendar file** to include a calendar invite with complete registration emails.
4. In the **Notifications for organizers** section:
   - Check **Enabled** to send organizers email notifications about new registrations.
5. Save changes by clicking **Save**.

#### **Step 2: Set Up Abstract Submission Notifications**
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

#### **Step 3: Send Manual Emails (Optional)**
**Location**: Management Area → Registration → Registrants → Email **or** Participants → Email
1. For registrants:
   - Go to **Registration → Registrants → Email**.
   - Select recipients (e.g., all registrants or specific groups like presenters).
   - Compose the email, attaching files or links as needed.
2. For meeting participants:
   - Go to **Participants → Email**.
   - Select participants and send custom emails.
3. For abstract authors:
   - Go to **Call for Abstracts → List of Abstracts → Email**.
   - Select specific abstracts and send emails to authors or reviewers.
4. Use rich text and placeholders for personalization.

---

### Example Scenario
For **National Research Conference 2025** (held 18 Aug - 20 Aug 2025):
- **Registration Confirmation**:
  > *Subject: Thank You for Registering – NRC 2025*  
  > *Dear {registrant_full_name},*  
  > *Thank you for registering for the National Research Conference 2025, held on 18–20 August 2025. Details will follow...*
- **Abstract Acceptance**:
  > *Subject: NRC 2025 – Abstract Accepted*  
  > *Dear {submitter_full_name},*  
  > *Your abstract titled "{abstract_title}" has been accepted for Session 3 on Aug 19.*

---

### Notes
- **Moderation**: Check **Moderated** under the registration form settings if approvals are required, triggering the "pending" message.
- **Placeholders**: Verify available placeholders in the template editor (e.g., `{registrant_full_name}`, `{abstract_title}`).
- **Testing**: Test notifications by submitting a test registration or using the preview feature (if available in v3.3.7).
- **Time Zone**: Ensure event times (e.g., 02:10 PM +0530 on 29 July 2025) align with your notification schedules.
- **Support**: Contact the Indico support team or refer to the Indico v3.3.7 documentation for additional guidance.

---

This guide is tailored to Indico v3.3.7 based on the screenshot and should work for your "National Research Conference 2025" setup. Let me know if you need further adjustments or help with specific configurations!
