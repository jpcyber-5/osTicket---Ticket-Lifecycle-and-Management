## osTicket - Tickets and Ticket Lifecycle

This section demonstrates how tickets are created, assigned, and resolved in the osTicket help desk system. It also highlights ticket properties, SLA configurations, department visibility, and typical real-world intake scenarios.

### Admin/Analyst Login Page
- `http://localhost/osTicket/scp/login.php`

### End User Portal
- `http://localhost/osTicket`

---

## Ticket Lifecycle Workflow

### Preparation
- Change the **SysAdmins Department** to a Top Level Department.
- **Delete** the **Maintenance Department** (do not archive it).

---

### Ticket 1: Banking System Outage
**Submitted By:** End-user  
**Issue:** "Entire mobile/online banking system is down"

**Help Desk Agent (John):**
- Observe ticket properties:  
  - Priority  
  - Department  
  - SLA  
  - Assigned To
- Set Properties:  
  - SLA: `Sev-A (1 hour, 24/7)`  
  - Department: `Online Banking`
- Observe ticket visibility as John after change  
- Resolve the ticket as Jane

---

### Ticket 2: Adobe Upgrade
**Submitted By:** End-user  
**Issue:** "Accounting department needs Adobe upgrade, broken"

**Help Desk Agent (John):**
- Observe ticket properties
- Set Properties:  
  - SLA: `Sev-B (4 hours, 24/7)`  
  - Department: `Support`
- Resolve ticket as John

---

### Ticket 3: CFO Laptop Failure
**Submitted By:** End-user  
**Issue:** "CFO’s laptop will no longer turn on"

**Help Desk Agent (John):**
- Observe ticket properties
- Set Properties:  
  - SLA: `Sev-B (4 hours, 24/7)`  
  - Department: `Support`
- Resolve ticket as John

---

### Ticket Permissions and Escalation
- After assigning **Sev-A** to a SysAdmins ticket, notice John cannot access it.
- Switch to **Admin Panel**, give John **View-access** to **SysAdmins**.
- Switch back to **Agent Panel** and confirm visibility.
- Observe restrictions on making changes to escalated tickets.

---

## Ticket Communication and IRL Application

- osTicket (and most help desk tools) support **email notifications**.
  - When tickets are updated, users receive an email copy and can respond.
- **Real-world ticket intake** may occur via:
  - Phone, chat apps, email, web form
  - In-person interaction (e.g., hallway requests)
- It's important to **create tickets for everything** for visibility and metrics.
  - Even for "quick fixes" or informal requests

---

## Finishing Up & Best Practices

- Practice using the email feature for real-time ticket updates
- Redo this lab multiple times using a checklist
  - Builds **intuition** and **technical confidence**
- Revisit the **Technical Skill Pillar**
  - Emphasize growth through repetition and lab mastery
