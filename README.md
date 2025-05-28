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

### 📩 Ticket 1: Banking System Outage
**Submitted By:** End-user  
**Issue:** _"Entire mobile/online banking system is down"_

**Help Desk Agent (John):**
- 🔍 Observe ticket properties:
  - Priority  
  - Department  
  - SLA  
  - Assigned To
- ⚙️ Set properties:
  - SLA: `Sev-A (1 hour, 24/7)`  
  - Department: `Online Banking`
- 🔒 Verify visibility restrictions after escalation
- ✅ Resolve the ticket as **Jane**

---

### 🧾 Ticket 2: Adobe Upgrade
**Submitted By:** End-user  
**Issue:** _"Accounting department needs Adobe upgrade, broken"_

**Help Desk Agent (John):**
- 🔍 Observe ticket properties
- ⚙️ Set properties:
  - SLA: `Sev-B (4 hours, 24/7)`  
  - Department: `Support`
- ✅ Resolve ticket as John

---

### 💻 Ticket 3: CFO Laptop Failure
**Submitted By:** End-user  
**Issue:** _"CFO’s laptop will no longer turn on"_

**Help Desk Agent (John):**
- 🔍 Observe ticket properties
- ⚙️ Set properties:
  - SLA: `Sev-B (4 hours, 24/7)`  
  - Department: `Support`
- ✅ Resolve ticket as John

---

### 👁️‍🗨️ Permissions and Escalation
- After assigning **Sev-A** to a **SysAdmins** ticket, John cannot access it.
- 🛡️ Use **Admin Panel** to grant **View-access** to **SysAdmins**
- 🔄 Switch back to **Agent Panel** to verify access
- ⚠️ Note: Escalated tickets may be visible but not editable

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

## 🏁 Wrapping Up & Best Practices

- ✉️ Test the email feature to understand communication flow
- 🔁 Revisit the lab until the workflow becomes second nature
- 📈 Repetition builds technical confidence and troubleshooting skill

