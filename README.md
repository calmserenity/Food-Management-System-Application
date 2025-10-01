# Food-Management-System-Application
A charity management systems that allows real-time tracking and updates on food items, volunteers and food bank. 

## Project Demo 
22078877_NgKarYeeSerene_OOPFinalAssignment.mkv

<img width="756" height="473" alt="image" src="https://github.com/user-attachments/assets/5a68b892-2bc6-4d00-baac-ce440d4ab9de" />
<img width="745" height="467" alt="image" src="https://github.com/user-attachments/assets/6050ba27-9e6b-4205-8693-19bd93727996" />
<img width="763" height="478" alt="image" src="https://github.com/user-attachments/assets/5ab04031-7fe1-4bcd-b556-588eb0c301f5" />
<img width="761" height="476" alt="image" src="https://github.com/user-attachments/assets/b19c002b-e0f3-4518-bd2c-21b0e04d7e91" />
<img width="766" height="481" alt="image" src="https://github.com/user-attachments/assets/9c4c1d1a-dad9-46b9-9443-7a9ee950ed89" />
<img width="725" height="455" alt="image" src="https://github.com/user-attachments/assets/19332c57-4dbf-4565-985a-66ea7014425f" />
more in the demo

## UML Diagram
<img width="3840" height="1293" alt="22078877_UML CLASS DIAGRAM" src="https://github.com/user-attachments/assets/59f766c9-65b3-46fc-afe5-b62586b77477" />

## Features & Functionality 
1. Authentication System

Secure login and registration with SHA-256 password hashing. Role-based access control supports both admin and standard users. Session management maintains user state, with logout clearing all session data.

2. Navigation System

Centralized navigation via MainApp with view history and role-based routing. A collapsible hamburger menu and dynamic headers allow intuitive movement across the app. Contextual views and browser-style back functionality enhance user experience.

3. Food Bank Management

Admins can create, edit, and view food banks using searchable, interactive UI cards. Detailed profiles include contact info, operating hours, and needs. Backed by safe database operations for consistency and accuracy.

4. Inventory Management

Admins manage inventory per food bank, adding items with quantity, category, and expiry. Automatic updates reflect donation approvals or requests. Real-time stock data and expiry tracking ensure food safety and availability.

5. Donation System

Users pledge donations through a dynamic form. Admins approve or reject donations, with inventory automatically updated upon approval. Users can track their donation history and status.

6. Request Management

Users can request food items from available inventory. Admins review and approve/reject based on stock availability. Approved requests deduct quantities automatically, ensuring accurate stock levels.

7. Volunteer Management

Users apply for volunteer slots, submitting availability. Admins approve, schedule, and manage sessions. Status tracking and formatted scheduling enhance coordination.

8. User Interface

Dynamic UIs with controller-based initialization, data binding, and context-aware updates. Role-based visibility and button state management ensure clear access control and navigation consistency.

9. Data Management

Model-based data access with type-safe CRUD operations. Setup includes schema creation and initial seeding. Strong relational integrity across users, donations, food banks, and volunteer sessions.

10. Validation & Error Handling

All inputs validated for completeness and correctness. User feedback provided via alerts with contextual messages. Fields reset after operations for improved UX.

11. Status Tracking

Users can monitor donations, requests, and volunteer statuses through color-coded tables. Real-time updates reflect administrative decisions and activity outcomes.
