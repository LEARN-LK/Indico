
## Part 3: I – Setup Email Notifications

This step helps you configure **automated email notifications** for your Indico conference to keep participants, reviewers, and organizers informed at every stage.

---

### Step-by-Step Tasks

#### **Step 1: Configure Registration Notifications**
**Location**: Management Area → Registration → Configure
1. Go to the **Management Area** of your event.
2. Click **Registration** → **Configure** (next to the Registration Form).
3. In the **Notification headers and text** section:
   - Customize email templates for registration confirmation, acceptance, or rejection.
   - Use placeholders like `{registrant_full_name}`, `{event_name}`, or `{registration_id}` (check the template editor for available placeholders).
4. Save changes by clicking **Save**.
5. To send invitations:
   - Click **Invite** in the **Registration** section.
   - Add participants (Indico users or external emails) and set **Skip moderation** to "Yes" for automatic acceptance.
   - Click **Send** to dispatch invitation emails with accept/decline links.

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
For **NRC 2025**:
- **Registration Confirmation**:
  > *Subject: Thank You for Registering – NRC 2025*  
  > *Dear {registrant_full_name},*  
  > *Thank you for registering for the National Research Conference 2025, held on 10–12 December 2025...*
- **Abstract Acceptance**:
  > *Subject: NRC 2025 – Abstract Accepted*  
  > *Dear {submitter_full_name},*  
  > *Your abstract titled "{abstract_title}" has been accepted for Session 3 on Dec 11.*

---

### Notes
- **Double-check placeholders** in the template editor to ensure accuracy (e.g., `{registrant_full_name}`, `{abstract_title}`).
- **Test emails** by using the preview feature or sending to your own email address.
- **Keep tone professional** and concise, avoiding excessive details.
- **Support**: Refer to the Indico.UN Help page or contact the support team for assistance with template setup or role permissions.

---

### Additional Notes
- **Indico Version**: The guide assumes a recent Indico version (e.g., 1.9.9 or later). Some features, like automatic organizer notifications for abstracts, may require manual configuration or support team assistance.
- **Permissions**: Ensure you have the **conference manager** or **category manager** role to access these settings. Contact Indico.UN support for role assignment.
- **Testing**: Always test notifications with a small group before sending to all participants.
- **Indico.UN Specifics**: Some features (e.g., e-tickets or room bookings) may be specific to UN venues and require additional configuration.

If you need further clarification or have specific questions about Indico’s interface, let me know, and I can tailor the guide further or check for updates via web or X posts if necessary.
