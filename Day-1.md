# CODE IQ HUB  

## Microsoft Azure Cloud Services  

### Day – 1 : Cloud Basics  

#### What to Learn  
- What is Cloud Computing  
- Cloud Service Models → IaaS, PaaS, SaaS  
- Benefits: Scalability, Flexibility, Pay-as-you-go, Security  

---

## What is Cloud Computing?  

- Cloud computing means using the internet to access servers, storage, databases, and services instead of buying and maintaining physical computers.  
- Cloud Computing is the delivery of computing services (like servers, storage, databases, networking, software, and more) over the internet.  
- Storing and processing data on a local computer or server, resources are accessed online from the cloud.  
- **Example:** Instead of buying a server for your website, you rent one from Azure and pay only for the hours you use it.  
- **Main Idea:** It’s like using electricity — you pay for what you use.  

---

## Cloud Service Models  

Cloud computing services are mainly divided into three models:  

### 1. Infrastructure as a Service (IaaS)  

**Definition:**  
- Provides virtualized computing resources over the internet — like renting hardware and networking components.  
- You manage the Operating System (OS), apps, and data, while the provider manages the physical servers, storage, and networking.  

**What You Manage:**  
- OS (Windows/Linux)  
- Applications  
- Data  
- Middleware  

**What Provider Manages:**  
- Physical servers  
- Networking  
- Storage  
- Virtualization  

**Examples:**  
- Microsoft Azure Virtual Machines  
- AWS EC2  
- Google Compute Engine  

**Analogy:**  
- Renting an empty apartment — you get the walls and roof, but you bring your own furniture and set it up.  

---

### 2. Platform as a Service (PaaS)  

**Definition:**  
- Provides a ready-to-use platform for developers to build, run, and deploy applications without managing infrastructure.  
- You only manage your applications and data, while the provider takes care of servers, OS, and runtime.  

**What You Manage:**  
- Applications  
- Data  

**What Provider Manages:**  
- OS & Runtime environment  
- Middleware  
- Networking, servers, and storage  

**Examples:**  
- Microsoft Azure App Service  
- Google App Engine  
- AWS Elastic Beanstalk  

**Analogy:**  
- Renting a fully furnished apartment — you just bring your belongings and start living, without worrying about maintenance.  

---

### 3. Software as a Service (SaaS)  

**Definition:**  
- Ready-made software applications delivered over the internet.  
- You just log in and use them.  
- You don’t manage anything — not servers, not OS, not runtime.  

**What You Manage:**  
- Just your data (sometimes not even that, e.g., Gmail).  

**What Provider Manages:**  
- Everything: servers, OS, applications, storage, networking.  

**Examples:**  
- Microsoft 365  
- Gmail  
- Salesforce  
- Dropbox  

**Analogy:**  
- Booking a hotel room — everything is ready; you just check in and use it.  

---

## Benefits of Cloud Computing (with Azure Examples)  

### 1. Scalability (Elastic Resources)  
- **Azure Features:**  
  - Azure Virtual Machine Scale Sets → Automatically adds/removes VMs based on demand.  
  - Azure App Service → Scales up (bigger instance) or out (more instances) in minutes.  
- **Example:**  
  - An e-commerce app hosted on Azure App Service adds more instances on Black Friday and reduces them afterward.  

---

### 2. Flexibility (Global Access & Options)  
- **Azure Features:**  
  - Azure Global Infrastructure → 60+ Regions worldwide → choose where to host.  
  - Hybrid Cloud Support → Azure Arc lets you manage on-premises + multi-cloud resources from one place.  
- **Example:**  
  - A company with offices in India and the US runs services in Central India and East US regions to give users faster access.  

---

### 3. Pay-as-You-Go (Cost Efficiency)  
- **Azure Features:**  
  - Azure Pricing Calculator → Estimate costs before deploying.  
  - Azure Cost Management + Budgets → Track and control expenses.  
  - Reserved Instances & Spot VMs → Save up to 80% for predictable workloads.  
- **Example:**  
  - A startup runs test workloads using Azure Spot VMs to save money, and only pays when VMs are available.  

---

### 4. Security (Enterprise-Grade Protection)  
- **Azure Features:**  
  - Azure Security Center → Monitors security posture & suggests improvements.  
  - Azure Active Directory (Azure AD) → Multi-Factor Authentication & Identity Protection.  
  - Compliance Certifications → ISO, HIPAA, GDPR, etc.  
- **Example:**  
  - A healthcare app uses Azure AD MFA to secure doctor logins and ensure HIPAA compliance.  

---

## Quick Azure-Based Summary  
- **Scalability:** Azure VM Scale Sets, App Service Autoscaling  
- **Flexibility:** Azure Arc, Multiple Global Regions  
- **Pay-as-You-Go:** Azure Cost Management, Spot VMs  
- **Security:** Azure Security Center, Azure AD, Compliance  
