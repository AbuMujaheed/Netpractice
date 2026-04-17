# Netpractice
*This project has been created as part of the 42 curriculum by sojetimi*

# 🌐 NetPractice

## 📌 Description

**NetPractice** is a networking training project designed to build a solid understanding of fundamental networking concepts through hands-on problem solving.

The goal of the project is to configure small network topologies correctly by assigning:

* IP addresses
* Subnet masks
* Routing tables

Each level presents a broken network that must be fixed so that all hosts can communicate with each other and with the Internet when required.

Through this project, key concepts such as routing, subnetting, and network segmentation are learned in a practical way.

## ⚙️ Instructions

### ▶️ Running the Training Interface

To start the NetPractice training interface:

```bash
./run.sh
```

This will open the interactive browser interface where you can:

* Solve network levels
* Edit IP configurations
* Modify routing tables
* Validate your solutions

---

### 💾 Exporting Configurations

After successfully solving a level:

1. Click **“Export”**
2. A `.json` file will be generated
3. Save it in your project repository

---

### 📤 Submission Requirements

* Submit the exported `.json` files for the required levels
* Ensure all levels are **validated (OK)**
* The repository must contain:

  * All required configuration files
  * This `README.md`

---

## 🧠 Concepts Learned

This project covers essential networking topics, including:

* **TCP/IP addressing**
* **Subnet masks and CIDR**
* **Default gateways**
* **Routing tables**
* **Routers vs switches**
* **OSI model layers**
* **Network segmentation**
* **Public vs private IP addressing**
* **Forward and reverse packet flow**
* **Route summarization**

---

## 🚀 Key Takeaways

* Each network link must belong to a **single subnet**
* Routers forward packets based on **routing tables**
* Internet communication requires **both forward and reverse paths**
* Incorrect subnet masks can cause **hidden routing errors**
* Large subnets (e.g. /18) can unintentionally **overlap networks**

## 📚 Resources
### 📖 Documentation & Tutorials
* https://www.cloudflare.com/learning/network-layer/what-is-an-ip-address/
* https://www.geeksforgeeks.org/computer-network-tcp-ip-model/
* https://www.ibm.com/docs/en/aix/7.2?topic=concepts-tcpip-addressing
* https://www.cisco.com/c/en/us/support/docs/ip/routing-information-protocol-rip/13788-3.html
* https://www.khanacademy.org/computing/computer-science/internet-intro

### 🤖 Use of AI
AI (ChatGPT) was used in this project to:
* Explain networking concepts (subnetting, routing, CIDR)
* Help debug incorrect routing configurations
* Provide guidance for solving complex
* Clarify packet flow and reverse routing issues

All solutions were **implemented, tested, and understood manually**.

## 🧩 Additional Notes

This project emphasizes **understanding over memorization**.
The ability to reason about networks, rather than guess configurations, is essential for success.

## ✅ Submission

Ensure that:

* All required levels are solved
* All configurations are exported correctly
* README is complete and clear

