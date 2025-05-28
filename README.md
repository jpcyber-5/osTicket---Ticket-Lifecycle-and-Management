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
- ⚙️ Set properties:
  - SLA: `Sev-A (1 hour, 24/7)`  
  - Department: `Jane (Online Banking)`
- 🔒 Verify visibility restrictions after escalation
- ✅ Resolve the ticket as **Jane**


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


