

##  **A. Conference Category Setup & Role Assignment**

###  Scenario:

The **University of Peradeniya** is hosting the **National Research Conference 2025** using the LEARN-hosted Indico platform. LEARN Admins only handle:

* Category creation (based on university names)
* Assigning university coordinators as **Category Managers**

From that point onward, the **University Manager** (e.g., Dr. Silva from UoP) handles event creation, abstract management, registration, and more.

---

###  **Admin Task: Create University Category & Assign Category Manager**

####  Steps:

1. **Login as Indico Site Admin**
   Go to: [https://ws.learn.ac.lk](https://ws.learn.ac.lk)

2. **Go to the Category Management Area**

   * Click the **🖉 pencil icon** at the top right of the homepage.

3. **Create Subcategory (University)**

   * Click **“+ Create subcategory”**
   * Fill in:

     * Title: `University of Peradeniya`
     * Description: `Events and conferences hosted by UoP`
   * Click **Create**

4. **Assign Category Manager (University Coordinator)**

   * Open the newly created subcategory (`University of Peradeniya`)
   * On the left menu, click **“Protection”**
   * Click **“Add”** under **Managers**
   * Search for the university user (e.g., `Dr. Silva`)
   * Assign roles (check appropriate privileges):

     * Can create events
     * Can manage protection
     * Can manage category


---
##  **Step H: Add Rooms & Venues**

The Room Booking plugin allows administrators to manage and book physical rooms and venues within Indico. Once the plugin is properly installed and activated, follow the steps below to add rooms.

---

###  Prerequisites

* You must be logged in as an **Indico administrator**.
* The `RoomBooking` plugin must be installed and enabled in `indico.conf`:

  ```ini
  ENABLE_ROOMBOOKING = True
  ```
* After updating the config, **restart Indico**.

---

### 🔹 1. **Open the Room Booking Module**

* From the top navigation bar, click **“Room Booking”**.
* If not visible, ensure the plugin is properly installed and active.

---

### 🔹 2. **Access the Administration Area**

* On the Room Booking homepage, click the **“Administration”** button (⚙️ icon) at the top-right corner.

---

### 🔹 3. **Add a New Room**

* In the left-hand **sidebar**, click on **“Locations”**.
* Then click the **“+ Add Room”** button at the top-right.

---

### 🔹 4. **Enter Room Details**

Fill in the room information such as:

| Field           | Example                    |
| --------------- | -------------------------- |
| **Room Name**   | Main Conference Hall       |
| **Site**        | University of Colombo      |
| **Building**    | Science Faculty            |
| **Floor**       | 1st                        |
| **Room Number** | SC-101                     |
| **Capacity**    | 150                        |
| **Type**        | Lecture Hall / Auditorium  |
| **Equipment**   | Projector, Mic, Whiteboard |

---

### 🔹 5. **Save the Room**

* Click **“Create Room”** to save the new room.

---

### 🧪 **Example Room Entry**

**Room Name**: Boardroom
**Site**: University of Ruhuna
**Building**: Administration Block
**Floor**: 2
**Room Number**: AD-201
**Capacity**: 25
**Type**: Meeting Room
**Equipment**: TV, HDMI, Conference Phone

---


