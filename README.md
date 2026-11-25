<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=hassan42772.hassan42772&left_color=060708&right_color=10b981" alt="visitor badge" />
  <br/><br/>
  <img src="https://github.com/hassan42772/hassan42772/blob/main/poster.png" alt="Hassan Maqbool Banner" />
</div>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Chakra+Petch&weight=700&size=32&pause=1000&color=47F59C&center=true&vCenter=true&width=620&height=65&lines=Hi+There!+I'm+Hassan+Maqbool;Full-Stack+MERN+%26+AI+Engineer;Building+Production+RAG+%26+Real-Time+Systems" alt="Typing SVG" />
</h1>

<h3 align="center">Full-Stack Web Developer (MERN) · AI & RAG Pipeline Engineer · IoT Systems</h3>

<div align="center">
  <a href="https://hassan-coder.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-060708?style=for-the-badge&logo=netlify&logoColor=47F59C" height="34" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/hassan-maqbool-dev" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-060708?style=for-the-badge&logo=linkedin&logoColor=47F59C" height="34" alt="LinkedIn" />
  </a>
  <a href="mailto:hassan427726g@gmail.com">
    <img src="https://img.shields.io/badge/hassan427726%40gmail.com-060708?style=for-the-badge&logo=gmail&logoColor=47F59C" height="34" alt="Email" />
  </a>
</div>

<br/>

<div align="center">
  <strong>Architecting low-latency full-stack applications, guarded Retrieval-Augmented Generation (RAG) pipelines, and real-time distributed systems.</strong>
</div>

<hr/>

## 👨‍💻 About Me

I am a **Full-Stack Software Engineer** and **AI Integration Developer** currently working at **ArhamSoft** (Chief Minister's IT Internship Program) with a **BS in Computer Science** (3.73/4.00 CGPA) from The Islamia University of Bahawalpur. I specialize in taking full-stack MERN applications and LLM-powered retrieval systems from schema design to tested, deployed production.

* 🧠 **AI & RAG Engineering:** Building multi-domain RAG pipelines with hybrid vector + keyword search (Reciprocal Rank Fusion), local cross-encoder re-ranking, Server-Sent Events (SSE) streaming, Attribute-Based Access Control (ABAC), and automated LLM-as-a-Judge evaluation suites.
* 💻 **Full-Stack Architecture:** Designing modular React & Node.js/Express systems backed by MongoDB, PostgreSQL (Supabase), and MySQL, secured with HTTP-only JWT cookies and input/moderation guardrails.
* 🧪 **Testing & API Reliability:** Enforcing backend stability with automated integration test suites (**Jest** & **Supertest**) and interactive **Swagger / OpenAPI** specifications.
* 🔌 **Embedded & IoT Systems:** 2 years of hands-on experience bridging hardware microcontrollers (Arduino, RFID, sensors) with real-time web monitoring dashboards.

<hr/>

## 🛠️ Tech Stack & Tooling

<div align="center">

**Frontend Engineering**<br/>
<img src="https://skillicons.dev/icons?i=js,react,redux,tailwind,html,css,vite" alt="Frontend Stack" />

**Backend & Databases**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,postgres,supabase,mysql" alt="Backend and Databases" />

**AI, RAG & LLM Infrastructure**<br/>
<img src="https://img.shields.io/badge/OpenAI_SDK-060708?style=for-the-badge&logo=openai&logoColor=47F59C" />
<img src="https://img.shields.io/badge/Gemini_API-060708?style=for-the-badge&logo=googlegemini&logoColor=47F59C" />
<img src="https://img.shields.io/badge/MongoDB_Atlas_Vector_Search-060708?style=for-the-badge&logo=mongodb&logoColor=47F59C" />
<img src="https://img.shields.io/badge/LangChain_%26_LangGraph-060708?style=for-the-badge&logo=chainlink&logoColor=47F59C" />
<img src="https://img.shields.io/badge/Transformers.js_(Local_Embeddings)-060708?style=for-the-badge&logo=huggingface&logoColor=47F59C" />
<img src="https://img.shields.io/badge/OpenRouter-060708?style=for-the-badge&logo=icloud&logoColor=47F59C" />

**Testing, Docs, DevOps & IoT**<br/>
<img src="https://skillicons.dev/icons?i=jest,git,github,postman,vercel,netlify,arduino" alt="Tools and Deployment" /><br/>
<img src="https://img.shields.io/badge/Swagger_OpenAPI-060708?style=for-the-badge&logo=swagger&logoColor=47F59C" />
<img src="https://img.shields.io/badge/Supertest-060708?style=for-the-badge&logo=testinglibrary&logoColor=47F59C" />
<img src="https://img.shields.io/badge/Railway-060708?style=for-the-badge&logo=railway&logoColor=47F59C" />

</div>

<hr/>

## 🚀 Featured Engineering Projects

### 🧠 Production-Grade Advanced RAG Chatbot
An enterprise-ready Retrieval-Augmented Generation system built on the MERN stack with strict access control, multi-stage retrieval, and automated quality evaluation.
* **Tech Stack:** React.js, Node.js, Express.js, MongoDB Atlas Vector Search, Gemini API, OpenAI SDK, OpenRouter, `@xenova/transformers`, LangChain
* **Key Architecture:**
  * **Hybrid Retrieval & Re-Ranking:** Combines dense vector search (`all-MiniLM-L6-v2` 384-dim local embeddings) and keyword search fused via **Reciprocal Rank Fusion (RRF)**, followed by local cross-encoder re-ranking (`ms-marco-MiniLM-L-6-v2`).
  * **Security & Governance:** Enforces **Attribute-Based Access Control (ABAC)** metadata filtering across isolated knowledge bases, input moderation guardrails (`omni-moderation-latest`), and prompt-injection defenses.
  * **Real-Time & Evaluated:** Streams responses token-by-token via **SSE**, supports incremental document ingestion, and achieved **1.00 context recall** and **1.00 faithfulness** on an automated Gemini LLM-as-a-Judge test suite.

### 💬 Real-Time Messaging & WebRTC Audio Platform
A full-stack communication platform engineered for low-latency messaging and direct peer-to-peer voice calls.
* **Tech Stack:** React.js, Node.js, Express.js, MongoDB, Socket.IO, WebRTC
* **Key Architecture:** HTTP-only JWT cookie authentication with Two-Factor Authentication (2FA), real-time 1-on-1 and group chat rooms, cursor-based infinite scroll pagination, and WebRTC peer-to-peer audio calling.

### 🔌 Automated RFID Attendance & IoT Smart Systems
* **Tech Stack:** Arduino Uno, RFID, I2C LCD, C++, Node.js, Express.js, MongoDB
* **Key Architecture:** Designed the hardware-to-cloud architecture for an automated RFID attendance tracker syncing scan logs to a MERN web dashboard, alongside embedded automation systems (Smart Solar Panel Cleaner, Smart Parking, and Smart Rain Shelter).

<hr/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Chakra+Petch&weight=600&size=22&pause=1000&color=47F59C&center=true&vCenter=true&width=520&height=50&lines=Open+to+Full-Stack+%26+AI+Engineering+Roles;Thanks+for+visiting!" alt="Footer Typing SVG" />
</div>
