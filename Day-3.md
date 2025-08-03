# CODE IQ HUB  

## Microsoft Azure Cloud Services – Day 3  

### Topics Covered  
- Azure Global Infrastructure Theory  
  - Regions  
  - Availability Zones  
  - Edge Locations  
- Why multiple regions exist (latency, compliance, disaster recovery)  

### Hands-on  
- Explore Azure Global Infrastructure  
- Mark 3 nearest Azure regions on a world map  

---

## Azure Global Infrastructure  

### 1. Azure Regions  
- A **Region** is a set of datacenters deployed within a geographic area.  
- Each region provides **redundancy and local access**.  
- **Examples:** Central India, East US, West Europe  
- **Fact (2025):** Azure has **60+ regions worldwide**, more than any other cloud provider.  

---

### 2. Availability Zones (AZs)  
- An **Availability Zone** is a physically separate datacenter within a region.  
- Each AZ has **independent power, cooling, and networking**.  
- Protects against **datacenter failures**.  
- **Example:** East US region has *3 Availability Zones*.  

---

### 3. Edge Locations  
- **Small datacenters** placed closer to users for **faster content delivery**.  
- Used for services like **Azure Content Delivery Network (CDN)**.  
- **Reduces latency** by caching data near end-users.  

---

## Why Multiple Regions Exist  

1. **Latency Reduction**  
   - Users connect to the nearest region for faster response.  
   - *Example:* Users in India use **Central India region** instead of Europe.  

2. **Compliance Requirements**  
   - Some countries require data to stay **within their borders**.  
   - *Example:* A bank in Germany must store data within Germany.  

3. **Disaster Recovery (High Availability)**  
   - If one region fails, another region can serve as backup.  
   - *Example:* Pairing **East US with West US** for failover.  

---

## 📝 Hands-On  

### Step 1: Explore Azure Global Infrastructure  
- Visit the [Azure Global Infrastructure Map](https://azure.microsoft.com/en-us/global-infrastructure/geographies/)  
- Search for your country and nearby regions.  

### Step 2: Mark 3 Nearest Azure Regions  
**If you are in India (example):**  
- **Central India** (Pune)  
- **South India** (Chennai)  
- **West India** (Mumbai)  

**Tip:**  
- Use **Google My Maps** (free tool) to place pins digitally.  
- Or draw them on a paper map for your notes.  

---

## ✅ At the End of Day 3, You Should Be Able To  
- Explain **Regions, AZs, and Edge Locations**  
- Know **why Azure uses multiple regions**  
- Identify **3 nearest regions to you**  
