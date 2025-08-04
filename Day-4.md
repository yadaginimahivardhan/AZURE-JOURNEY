# CODE IQ HUB  

## Microsoft Azure Cloud Services – Day 4  

### Topics Covered  
- Shared Responsibility Model Theory  
- What Microsoft manages vs what the customer manages  
- Security responsibilities for IaaS, PaaS, SaaS  

### Hands-on  
- Create a chart splitting responsibilities (Microsoft vs You)  

---

## What is the Shared Responsibility Model?  

In cloud computing, **Microsoft Azure** and the **customer** share responsibilities for security and management:  

- **Microsoft (Azure)** → Secures the **cloud infrastructure**  
- **Customer (You)** → Secures **what you put in the cloud**  

---

## What Microsoft Manages  
- Physical Datacenters (buildings, electricity, cooling)  
- Networking & Physical Security  
- Physical Hosts & Storage Hardware  
- Foundation Infrastructure (hypervisors, virtualization layer)  

---

## What the Customer Manages  
- **Identity & Access Management** (who can log in, MFA, roles)  
- **Data** (files, databases, backups, encryption)  
- **Applications** (patching, securing, updating)  
- **Configuration** of network & resources  
- **Compliance** with laws/regulations  

---

## Security Responsibilities by Service Model  

| Service Model | Microsoft Manages | Customer Manages |
|--------------|------------------|-----------------|
| **IaaS** (e.g., Azure VMs) | Datacenters, Physical Hosts, Networking | OS, Applications, Data, Network Configurations |
| **PaaS** (e.g., Azure App Service) | Datacenters, Hosts, Networking, OS, Runtime, Middleware | Applications, Data, Access Control |
| **SaaS** (e.g., Microsoft 365) | Everything: Datacenters, Networking, OS, Application | Data, User Access & Identity |

---

## 📝 Hands-On Task: Create a Shared Responsibility Chart  

| Area | Microsoft (Azure) | Customer (You) |
|------|------------------|----------------|
| **Datacenters & Hardware** | ✅ | ❌ |
| **Networking** | ✅ | ❌ |
| **Operating System** | IaaS: ❌ <br> PaaS/SaaS: ✅ | IaaS: ✅ <br> PaaS/SaaS: ❌ |
| **Applications** | PaaS/SaaS: ✅ | IaaS: ✅ <br> PaaS: ✅ |
| **Data & Access Control** | ❌ | ✅ |
| **Compliance Settings** | ❌ | ✅ |

✅ = Managed by Microsoft  
❌ = Managed by Customer  

---

## ✅ At the End of Day 4, You Should Be Able To  
- Explain the **Shared Responsibility Model**  
- Identify what **Microsoft vs Customer** is responsible for  
- Understand security roles in **IaaS, PaaS, and SaaS**  
- Create and use a **Shared Responsibility Chart**  
