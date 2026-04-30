# Azure Industrial Drive | Enterprise Admin Console

![Azure Status](https://img.shields.io/badge/Azure-Active-0078d4?style=flat&logo=microsoft-azure)
![AI-Powered](https://img.shields.io/badge/Gemini_AI-Enabled-8E75B2?style=flat&logo=google-gemini)
![Security](https://img.shields.io/badge/Security-TLS_1.3-success)
![Interface](https://img.shields.io/badge/UI-Industrial_Dark-black)

A high-performance, industrial-grade storage management interface designed for high-availability cloud environments. This console facilitates seamless interaction with Azure Blob Storage, real-time telemetry monitoring, and AI-assisted resource optimization.

---

## 📺 System Demonstration
Below is a walkthrough of the Multi-Tenant Enterprise Cloud Drive interface, showcasing the authentication flow, resource explorer, and AI integration.

<video src="https://github.com/Subhagaya-Git/Multi-Tenant-Enterprise-Cloud-Drive/blob/21033553082b07b59bb9383e1a170e9d820e2029/Final.mp4" controls="controls" style="max-width: 100%;">
  Your browser does not support the video tag.
</video>

---

## 🏗️ Core Architecture

* **Cloud Resource Explorer:** Automated listing, high-speed deployment (upload), and secure purging of cloud assets.
* **Gemini AI Integration:** A contextual AI assistant that processes storage metadata to provide optimization insights.
* **Performance Telemetry:** Live I/O stream monitoring for tracking latency and request status codes.
* **Predictive Financial Modeling:** Real-time calculation of storage expenditure based on active data volume.
* **Industrial UI/UX:** A responsive, high-contrast interface modeled after the Microsoft Azure design language.

## 🛠️ Technical Implementation

| Component | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Modern Grid/Flex), ES6+ JavaScript |
| **Cloud Provider** | Microsoft Azure (Blob Storage API) |
| **Artificial Intelligence** | Google Gemini 1.5 Flash LLM |
| **Analytics Engine** | Chart.js (Asynchronous Data Visualization) |
| **Protocol** | HTTPS / TLS 1.3 |

## 📂 Project Structure

```text
.
├── index.html      # Main Application Layer & Logic
├── style.css       # Azure Industrial Design Stylesheet
└── README.md       # Technical Documentation
⚙️ Configuration & Deployment
1. Cloud Authentication
To initialize the connection to your Azure environment, configure the CONFIG object within the source code:

JavaScript
const CONFIG = {
    sas: "YOUR_STORAGE_SAS_URL",
    geminiKey: "YOUR_GEMINI_API_KEY"
};
2. Authentication Protocol
Access to the dashboard is protected by a secure local identity provider. Standard administrative credentials are required to bypass the Cloud Identity overlay and access the resource management features.

3. Usage Instructions
Launch the application via any modern browser environment.

Authenticate via the Cloud Identity secure portal.

Monitor real-time Performance Logs to ensure low-latency IO operations.

Utilize the Gemini AI Sidebar for natural language queries regarding your storage context.

🔒 Security & Compliance
This console implements RBAC (Role-Based Access Control) simulations and utilizes SAS (Shared Access Signatures) to ensure granular security. For production deployments, it is recommended to proxy all storage requests through a secure backend (e.g., Node.js or Azure Functions) to prevent client-side credential exposure.

Optimized for Industrial Cloud Management and Enterprise Data Workflows.
