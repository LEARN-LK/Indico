##  **Part 3: L – Customize Certificates and Generate Participation Documents (Indico v3.3.7)**

###  **Step-by-Step Instructions**

---

### **Step 1: Access the Certificate Generator**

 **Navigation Path:**
**Management Area → Customize → Documents Template**

1. Go to the event’s **Management Area**.
2. Click on **Customize** in the left-hand menu.
3. Select **Documents Template**.
4. Click **➕ Add New** to create a new document.
5. Choose **Certificate of Attendance (V1)** from the available options.

---

### **Step 2: Customize the Template**

You’ll now see several customizable fields. Here's what each field does, with sample content using dynamic parameters.

####  **You can click “Sample Parameters”** to view the list of dynamic tags you can include. These include:

* `{name}` – Participant's full name
* `{event_title}` – Title of the event
* `{start_date}` – Event start date
* `{end_date}` – Event end date
* `{affiliation}` – Participant’s organization
* `{role}` – Role in the event (e.g., Speaker, Attendee)
* `{category}` – Contribution type (e.g., Poster, Talk)
* `{track}` – Track name, if applicable
* `{contribution_title}` – Title of the participant’s presentation (if any)

---

### **Customize Each Field (with Examples)**

| Field                        | Description                                     | Example                                                                                                                                    |
| ---------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Document Title**           | Title displayed on top of the certificate.      | `Certificate of Participation`                                                                                                             |
| **Organizer Address**        | Name and address of the organizing institution. | `University of Peradeniya, Faculty of Science, Peradeniya, Sri Lanka`                                                                      |
| **Venue**                    | Physical or virtual venue.                      | `University Senate Hall` or `Zoom Platform (Online)`                                                                                       |
| **Logo**                     | Upload a logo image.                            | *(Click “Upload Logo” and choose your image)*                                                                                              |
| **Certificate Text**         | Main certificate message, using dynamic tags.   | `This is to certify that {name} from {affiliation} has participated in the {event_title} held from {start_date} to {end_date} at {venue}.` |
| **Place of Signature (1st)** | Name and title of signatory 1.                  | `Dr. S.K. Perera\nChairperson – NRC 2025`                                                                                                  |
| **Place of Signature (2nd)** | Name and title of signatory 2.                  | `Prof. N. Jayasena\nDean – Faculty of Science`                                                                                             |
| **Place of Signature (3rd)** | (Optional) Name and title of a third signatory. | `Mr. R. Gunasekara\nConference Secretary`                                                                                                  |

---

### **Step 3: Save the Template**

* Click **Save** after completing the fields.
* Optionally, use the **Preview** feature to check how the certificate looks with real sample data.

---

### **Step 4: Generate Certificates for Participants**

 **Location:**
**Management Area → Participants → Registration → Generate Documents**

1. Navigate to **Participants** → **Registration**.
2. Use checkboxes or filters (e.g., attendance status) to select the participants.
3. Click **Generate Documents**.
4. Choose your saved certificate template.
5. Click **Generate PDFs** and download them.

---

### **Step 5 (Optional): Email the Certificates**

After generating:

* Use the **Email** option (if enabled) to send certificates as attachments to each participant automatically.

---

### 🧾 **Final Certificate Text Example (with Parameters)**

```
This is to certify that {name} ({affiliation}) has actively participated as a {role} in the National Research Conference 2025, held at {venue} from {start_date} to {end_date}.

We appreciate their valuable contribution and presence at this event.
```

---

Would you like help generating a PDF preview layout for testing, or writing Sinhala/English bilingual certificate text?
