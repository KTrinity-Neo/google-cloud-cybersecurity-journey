# 📅 Day 01 — Google Cloud Cybersecurity

## 🎯 Today's Objective

Today I began my Google Cloud Cybersecurity learning journey — covering the structure of the certificate program, core cloud computing concepts, deployment models, virtualization, and cloud storage fundamentals.

---

## 📚 What I Learned

### 1. Program Structure
The Google Cloud Cybersecurity Certification Programme covers:
- A. Introduction to Security Principles in Cloud Computing
- B. Strategies for Cloud Security Risks: Identify & protect against threats
- C. Detect, Respond & Recover from Cloud Cybersecurity Threats
- D. Prepare for a Cloud Security Analyst job

### 2. Cloud Computing Fundamentals
On-premise vs. Cloud Service Provider (CSP) models, data centers, zones/regions, and the core building blocks of cloud infrastructure (compute, storage, networking).

### 3. Cloud Storage & Data Management
Data types, storage classes, and how storage availability affects cost.

---

## ☁️ Google Cloud Concepts

- **On-premise:** Technology infrastructure that's physically located in an organization's own data center or office
- **CSP (Cloud Service Provider):** e.g. AWS, Google Cloud, Microsoft Azure
- **Data Center:** A physical building that houses servers, computer equipment & other components together
- **Zone:** A collective number of data centers in an area
- **Region:** A group of zones
- **Digital Transformation:** When an organization modernizes its applications, infrastructure, etc. using new technology
- **Cloud Deployment Models:**
  - *Public cloud* — delivers computing, storage & network resources over the internet, allowing users to share on-demand resources
  - *Private cloud* — cloud resources dedicated to a single user/organization, hosted on-premises or in a single-tenant environment
  - *Hybrid cloud* — combines public & private cloud models, giving more than one environment for using cloud services
- **Cloud Benefits:** Security, Scalability, Cost savings, Collaboration, Time to market
- **Cloud Limitations:** Shift in infrastructure control, Security concerns, Migrating existing legacy systems
- **Cloud Computing:** The practice of using remote servers hosted over the internet to run workloads
- **Ephemerality:** The concept that things only exist for a short amount of time
- **3 Main Categories of Cloud Computing Resources:** Compute, Storage, Networking
- **Virtualization:** Technology that creates a virtual version of physical infrastructure (servers, storage, networks)
- **Virtual Machine (VM):** The abstraction layer that creates a virtual version of the physical infrastructure
- **Hypervisor:** The software that creates and runs a VM
  - Type 1 = **Bare Metal**
  - Type 2 = **Hosted**
- **Advantages of VMs:** Portability, Scalability, Testing environments
- **Container:** A software package that holds only the components necessary to execute a particular application
- **Container stack:** Containerized apps → Container Engine → Host OS → Infrastructure
- **Container Key Benefits:** Portability, Immutability, Responsibility separation
- **Serverless Computing:** A cloud computing model where servers are abstracted from development (servers still exist, but are fully managed by the CSP)
  - **BaaS** (Backend as a Service) — CSP manages all aspects of the backend infrastructure
  - **FaaS** (Function as a Service) — runs functions (small pieces of code)

---

## 🔐 Cybersecurity Concepts

- **Resiliency:** The ability to prepare for, respond to, & recover from disruptions
- **Redundancy:** The practice of having multiple copies of data in different locations
- **Failure Domain:** A physical or virtual component that can fail without impacting the availability of other components
- **Latency:** The time it takes for data to travel from one location to another
  - NB: The lower the latency, the better a page loads — research shows 53% of users will leave a webpage if it doesn't load within 3 secs
- **Cloud Data Storage:** A solution that enables organizations to keep, access & maintain digital data on off-site, cloud-based storage devices
  - **Benefits:** Scalability, Redundancy, Cost savings, Security
- **Types of Data Stored:**
  - *Structured data* — organized in a certain format, like rows & columns
  - *Unstructured data* — not organized in any easily identifiable way
- **Data Types (storage):** Files, Objects, Block
- **Repository:** A centralized place to store, download & share data
- **Bucket:** A virtual container that holds objects (public/private), used to store & organize large amounts of unstructured data (e.g. audio files)
- **Hot data:** Data users access frequently
- **Cold data:** Data infrequently or rarely accessed
  - NB: The more available your data needs to be, the more it costs to store
- **4 Cloud Storage Classes:**
  1. **Standard** — best for hot data / data you need to access frequently, for short time periods
  2. **Nearline** — best for data accessed up to once a month; more cost-effective than standard, good for backups
  3. **Coldline** — for data accessed once every 90 days/quarter; very cost-effective
  4. **Archival** — best for archiving/disaster recovery; e.g. accessed once a year
- **File Storage:** Uses a hierarchy of files in folders; ideal for smaller volumes of data a few people need access to (e.g. files on a family computer)

---

## 🧪 Hands-on Practice

**Activity:** N/A — today was notes/theory only, no lab work yet

**What I did:** Took handwritten notes covering the program overview and Course 1 foundational concepts

**What happened:** Nothing Special Just learning 

---

## 💡 What I Understand Now

Before today's lesson:
> I didn't know the distinction between cloud deployment models (public/private/hybrid) or how storage classes (Standard/Nearline/Coldline/Archival) are priced based on access frequency.

After today's lesson:
> I can now explain the difference between VMs and containers, how serverless computing (BaaS/FaaS) still relies on CSP-managed servers, and how to choose the right storage class based on how often data needs to be accessed.

---

## ⚠️ Challenges

What I found difficult:
> Distinguishing ephemerality and failure domains from redundancy/resiliency — the terms felt similar at first.

How I addressed it:
> Broke each term down with its own definition and an example (e.g. redundancy = multiple copies of data in different locations vs. resiliency = ability to recover from disruption).

---

## 📝 Key Takeaways

1. Cloud storage classes exist on a cost-vs-access-frequency spectrum: Standard (frequent) → Nearline → Coldline → Archival (rarest).
2. Containers vs. VMs: VMs virtualize whole machines via a hypervisor; containers package only what's needed to run an app, sharing the host OS.
3. Serverless doesn't mean "no servers" — it means the CSP fully manages the servers so developers don't have to.

---

## 🎯 Next Step

Tomorrow I plan to learn:
> Continue into Course 1 — cloud security roles/responsibilities, and start Course 2 on identity and access management concepts.

---

## ⏱️ Study Time

**Time spent:** ~2 hrs (note-taking across 4 pages of material)

---

### 🚀 Progress

**Day 01 completed ✅**
