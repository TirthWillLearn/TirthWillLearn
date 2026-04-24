### Hi there! <img src="https://emojis.slackmojis.com/emojis/images/1536351075/4594/blob-wave.gif" width="25"/>

I'm **Tirth Patel**, a Backend Developer based in Mumbai, India.

⚡ Focused on building backend systems that handle concurrency, data consistency, and real-time communication.

I build **transaction-safe REST APIs and real-time systems** using Node.js, TypeScript, and PostgreSQL — with a focus on **concurrency control, authentication, and scalable backend design**.  
My projects are containerized with Docker and deployed on AWS (EC2, RDS).

---

### 🚀 Projects

**🛒 Multi-Vendor Order Management API**  
Handles concurrent order placement using PostgreSQL transactions and row-level locking to prevent overselling and ensure data consistency in multi-user scenarios.  
Implements atomic order creation with stock validation to eliminate race conditions.

Tech: Node.js · TypeScript · PostgreSQL · JWT · RBAC · Docker · AWS  
→ [Live](https://order-management-api-ruqo.onrender.com/) | [GitHub](https://github.com/TirthWillLearn/Order-Management-API) | [Docker](https://hub.docker.com/r/itstirthpatel02/order-management-api)

---
**💬 Real-Time Chat App**  
Single-server real-time messaging system built using Socket.io (WebSockets). Implements Redis-based presence tracking with a 30s TTL to manage online/offline status, and limits message history (50 messages) for efficient querying and performance.  
Includes JWT-based socket authentication.  
Uses TTL-based presence instead of relying solely on socket disconnect events to handle unexpected client drops.  
Designed as a single-server system with a clear upgrade path to horizontal scaling using Redis Pub/Sub.  

Tech: Node.js · Socket.io · Redis · PostgreSQL · JWT  
→ [GitHub](https://github.com/TirthWillLearn/Realtime-Chat-API)

---

**📚 Bookstore API**  
REST API with authentication, role-based access, and MySQL database integration, deployed on AWS RDS.  
Tech: Node.js · Express · MySQL · JWT  
→ [Live](https://bookstore-api-czay.onrender.com/) | [GitHub](https://github.com/TirthWillLearn/Bookstore-api)

---

### 🧠 Core Skills

- REST API design & backend architecture  
- Authentication & authorization (JWT, RBAC)  
- SQL transactions & concurrency control  
- Real-time systems (WebSockets, Redis)  
- Cloud deployment (AWS EC2, RDS, Docker)

---

### 📈 Currently Strengthening

- Distributed systems & scaling patterns  
- AWS (EC2, RDS, IAM, S3)  
- Data structures for backend problem solving  

---

📌 **For detailed breakdowns, architecture, and implementation decisions:**  
Check out my project repositories below 👉 
**[Full GitHub Profile README](https://github.com/TirthWillLearn/Tirth-Patel-)**
