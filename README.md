<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

## 🧾 osTicket - Tickets and Ticket Lifecycle

This section demonstrates how tickets are created, assigned, and resolved in the osTicket help desk system. It also highlights ticket properties, SLA configurations, department visibility, and real-world intake scenarios.

### 🔐 Admin/Analyst Login Page
- `http://localhost/osTicket/scp/login.php`

### 🌐 End User Portal
- `http://localhost/osTicket`

---

## 🔄 Ticket Lifecycle Workflow

### 🛠️ Preparation
- Change the **SysAdmins Department** to a **Top Level Department**
- **Delete** the **Maintenance Department** (do not archive)

---


### 📩 Ticket: Banking System Outage
**Submitted By:** Karen (End-user)  
**Issue:** _"Entire mobile/online banking system is down"_
![Screenshot 2025-05-28 161154](https://github.com/user-attachments/assets/ab87cce8-0221-4e51-8290-bb9e81584202)

![Screenshot 2025-05-28 161350](https://github.com/user-attachments/assets/f18e7eb4-3900-4ebe-93d1-101ca862c037)

![Screenshot 2025-05-28 161441](https://github.com/user-attachments/assets/4f1a064b-c6f6-45e5-adab-bfa8d21e24fb)

---
**Help Desk Agent (John):**

![Screenshot 2025-05-28 161522](https://github.com/user-attachments/assets/31243d7d-9762-4547-9dc1-a0544b72284a)

![Screenshot 2025-05-28 161542](https://github.com/user-attachments/assets/b8f178c8-5ea5-4cfe-b486-94690f042b4c)

---
- 🔍 Observe ticket properties:
  - Priority  
  - Department  
  - SLA  
  - Assigned To
 ![Screenshot 2025-05-28 161940](https://github.com/user-attachments/assets/aab32de4-143c-478b-a487-87f076516992)

---


- ⚙️ Set properties:
  - SLA: `Sev-A (1 hour, 24/7)`  
  - Department: `Jane (Online Banking)`
 ![Screenshot 2025-05-28 162257](https://github.com/user-attachments/assets/4d044809-773f-4a5e-a940-597713eb9047)

---


- ✅ Resolve the ticket as **Jane**


![Screenshot 2025-05-28 162457](https://github.com/user-attachments/assets/a9f37f36-57ff-47d5-ab5f-fcc8a4d90c7d)

![Screenshot 2025-05-28 162611](https://github.com/user-attachments/assets/22a99b4d-033d-4a4c-ac6a-038fb8f1f422)

![Screenshot 2025-05-28 163548](https://github.com/user-attachments/assets/be537d00-583c-4473-9581-b2a7541c25c8)

![Screenshot 2025-05-28 163751](https://github.com/user-attachments/assets/b4cfe540-0b48-4d75-b1b4-78a30ebf8c9f)

---

## 📬 Ticket Communication & Real-World Usage

- osTicket supports **email notifications**:
  - Users receive updates and can reply directly 💬
- Typical intake sources:
  - 📞 Phone  
  - 💻 Chat apps  
  - 📧 Email  
  - 📝 Web form  
  - 🤝 In-person requests
- 🧠 Pro tip: **Log every request** in the system for tracking and metrics

---


