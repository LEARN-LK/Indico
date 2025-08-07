#  Steps to Use Room Booking for “National Research Conference 2025”

> This guide outlines how to set up and manage room bookings for the **National Research Conference 2025**, including how to add a location, assign permissions to a location manager (e.g., Dr. Silva), book a room, and optionally link it to the event timetable.

---

###  1. Navigate to the Event

* Log in to your Indico instance.
* From the homepage or dashboard, find and select the event:
  **National Research Conference 2025**

---

###  2. Access the Room Booking Section

1. On the event page, click the **gear icon** or **“Manage event”** to open the **Management Area**.
2. In the left sidebar, scroll down and click **Room bookings**.
3. You’ll see the **Room bookings** tab with options. Click **“Book a room”** to open the Room Booking Dashboard.

---

###  3. Open the Room Booking Dashboard

* Once inside the Room Booking interface, click the **Administration** tab in the right-hand sidebar to configure room booking settings.

---

### 4. Add a New Location

1. In the left sidebar under **General Settings**, click **Locations**.
2. Click the **➕ Add** button in the top-right.
3. In the **Add Location** popup, fill in the details:

   * **Name**: `Auditorium`
   * **Room name format**: e.g., `{building}/{floor}-{number}`
     (e.g., `Auditorium/1-001`)
   * **Map URL template** *(optional)*: e.g.,
     `https://maps.example.com?room={building}/{floor}-{number}`
4. Click **Add** to create the location.

---

###  5. Assign a Location Manager (e.g., Dr. Silva)

1. From the Room Booking dashboard, go to:
   **Room Booking → Permissions**
2. Click the **+** button under **User** or **Group**.
3. Search for **Dr. Silva** (Conference Manager).
4. Grant Dr. Silva the following rights:

   * ✅ **Can manage bookings**
   * ✅ **Room manager** *(if required for location approval)*
5. Click **Add** to apply the permissions.

---

### 🔹 6. Book a Room

1. From the Room Booking interface:

   * Select the newly added **Location** (e.g., `Auditorium`)
   * Set the **Date Range**: `8 Sep – 13 Sep 2025`
   * Set the **Time Range**: e.g., `09:00 – 17:00`
   * Filter by capacity or equipment if needed.
2. Click **Search** to view available rooms.
3. Click **Book** next to the room (e.g., `Auditorium/1-001`)
4. Fill in the booking form:

   * **Reason**: e.g., *“Conference Session”*
   * Confirm or adjust the selected time/location
5. Click **Submit**

> If room booking moderation is enabled, Dr. Silva will need to approve the request via **Bookings in My Rooms**.

---

### 🔹 7. Manage and Verify Bookings

* View bookings under **My Bookings** in the sidebar.
* Dr. Silva (or other managers) can review all requests in **Bookings in My Rooms**.
* Edit or cancel bookings as needed.

---

### 🔹 8. Link Room to Timetable (Optional)

1. Go to the event’s **Management Area → Timetable**
2. Click **Add new session** or edit an existing one.
3. Assign the booked room (e.g., `Auditorium/1-001`) to the session.
4. Save your changes.

This allows participants to see room allocations directly from the event schedule.

---

## 🔍 Notes

* 🔐 **Permissions**: You must be an Indico admin or have appropriate rights to access Room Booking administration features.
* 📅 **Current Date**: August 07, 2025 — ensure bookings fall within the event range (8–13 September 2025).
* 🛑 **Moderation**: If enabled, location managers must approve bookings manually.
* 🛠 **Troubleshooting**:

  * If you can’t add locations or assign permissions, contact your Indico admin.
  * If the booking interface doesn’t work, check browser compatibility or reload the page.

---

Let me know if you’d like this turned into a PDF or integrated into your full event management guide.
