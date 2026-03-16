# Product Management Internship - UI Specification Case Study

This repository showcases my solution for a Technical Assessment Task during a **Product Management** application process.

## Case Description
The task required analyzing a "User Management" screen wireframe and preparing a comprehensive specification document for software developers.

### 1. General Layout
On the top of the page, we have global toolbar "new user" (button), "hide disabled user" (checkbox) and "save user" (button). 

Although it is not clear from the picture, the "new user" button might trigger a pop-up new user form page. (In the picture, we are observing the phase after we clicked the button).

Then, the page is split into a user table (left) and new users form (right). This aims to add new users and list them simultaneously.

### 2. User Table
**Data Columns:**
* ID - Unique
* User Name
* Email
* Enabled

Column headers are interactive. We should change the sort order by a single click (indicated by the arrow icons). The funnel icons in the header row should trigger a column-specific filter.

### 3. New User Form
* **Username:** Text
* **Display Name:** Text
* **Phone:** Numeric
* **Email:** Email
* **User Roles:** Multi-select Dropdown (Guest, Admin, SuperAdmin)
* **Enabled:** Checkbox

*Note: Mandatory fields are not clear on the picture.*

### 4. User Flow
1. User clicks the "new user" button in the top left.
2. New User Form pops up on the right.
3. User fills in the required fields.
4. User clicks the "save user" button.
5. Side panel closes. (Depending on usage frequency, the panel can either stay open for several entries or close automatically to save space.)
6. User Table automatically refreshes and displays the new user.

---
**Tunahan Gökgöz** [tunagokgoz19@gmail.com](mailto:tunagokgoz19@gmail.com)
