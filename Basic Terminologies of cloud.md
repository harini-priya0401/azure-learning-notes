# ☁️ Cloud Computing  

Cloud computing means using the **data centers of cloud providers** to store, run, and manage your applications and services **over the internet**, instead of relying only on your own physical servers.  

---

## 🔹 Types of Cloud  

### 🌐 Public Cloud  
- Services offered over the internet by providers like **Azure, AWS, GCP**.  
- Shared by many customers.  
- **Example:** Azure Virtual Machines.  

### 🏢 Private Cloud  
- Cloud infrastructure dedicated to a **single organization**, managed internally or by a vendor.  
- **Example:** A company’s own datacenter cloud setup.  

### 🔗 Hybrid Cloud  
- Combination of **Public + Private clouds**, connected securely to share data/applications.  
- **Example:** Banking apps (private cloud for sensitive data + public cloud for customer portals).  

---

## 🖥️ Server  
A **server** is a powerful computer that provides resources, data, or services (like websites, databases, apps) to other computers (clients).  

---

## 🌀 Virtualization  
Virtualization allows multiple **Virtual Machines (VMs)** to run on a single physical server using a **hypervisor**.  
✅ Increases efficiency  
✅ Reduces cost  

---

## 🏢 Data Center  
A **data center** is a large facility that houses servers, storage, and networking equipment.  
Cloud providers like **Microsoft Azure** and **Amazon AWS** have **global datacenters**.  

---

## 📍 Availability Zone (AZ)  
- A **physically separate datacenter** within a cloud region.  
- Independent power, cooling, and networking.  
- Designed for **fault tolerance**.  

---

## 🌍 Region  
- A **geographical area** (e.g., *East US*, *Central India*) that contains multiple availability zones.  
- Choosing the right region helps:  
  - Reduce **latency**  
  - Ensure **compliance** with local regulations  

---

## 📈 Scalability  

**Scalability** is the ability of a system to **increase or decrease resources** (CPU, memory, servers) as demand changes.  

- 🔼 **Vertical Scaling** → Upgrading the server (add more CPU/RAM).  
- ➕ **Horizontal Scaling** → Adding more servers.  

---

## 🔄 Elasticity  
**Elasticity** = Automatic scaling.  
- Resources are **added or removed dynamically** based on demand.  
- **Example:** An e-commerce app scaling up during festive sales and scaling down afterward.  

---

## ⚡ High Availability (HA)  
Designing systems so that services stay **available with minimal downtime**, even if hardware/software fails.  
Achieved through:  
- ✅ Redundancy  
- ✅ Load Balancing  
- ✅ Multiple AZs / Regions  
