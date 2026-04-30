# Azure Industrial Drive | Admin Console

![Azure Status](https://img.shields.io/badge/Azure-Active-0078d4?style=flat&logo=microsoft-azure)
![AI-Powered](https://img.shields.io/badge/Gemini_AI-Enabled-8E75B2?style=flat&logo=google-gemini)
![Security](https://img.shields.io/badge/Security-TLS_1.3-success)

A high-performance, industrial-grade cloud storage management interface. This console provides a streamlined dashboard for managing Azure Blob Storage resources, monitoring performance telemetry, and interacting with an integrated AI assistant for storage optimization.

---

## 🚀 Key Features

* **Cloud Resource Explorer:** Real-time listing, reading, and deletion of blobs from Azure containers.
* **Gemini AI Assistant:** Integrated AI sidebar to ask questions about your storage context and cloud management.
* **Performance Telemetry:** Live I/O ping monitoring and status logging.
* **Security Center:** Built-in views for Network Security (TLS 1.3) and RBAC Access Control.
* **Predictive Costing:** Real-time AI-driven cost calculation based on current data volume.
* **Responsive UI:** Clean, dark-mode "Azure Portal" aesthetic built for high-resolution industrial displays.

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3 (Modern Flex/Grid), JavaScript (ES6+)
* **Cloud Infrastructure:** Microsoft Azure Blob Storage
* **AI Integration:** Google Gemini 1.5 Flash API
* **Data Visualization:** Chart.js (Doughnut charts for usage tracking)
* **Security:** Session-based authentication and SAS (Shared Access Signature) tokenization.

## 📂 Project Structure

```text
.
├── index.html      # Main dashboard and logic
├── style.css       # Azure-themed industrial design
└── README.md       # Project documentation
⚙️ Getting Started
1. Prerequisites
To run the live cloud operations, ensure you have:

An active Azure Storage Account.

A SAS Token with Read, Write, Delete, and List permissions.

A Google Gemini API Key for the assistant features.

2. Configuration
Open index.html and update the CONFIG object with your credentials:

JavaScript
const CONFIG = {
    sas: "YOUR_AZURE_SAS_URL",
    geminiKey: "YOUR_GEMINI_API_KEY"
};
3. Usage
Open index.html in any modern web browser.

Sign In using the default administrative credentials:

Username: Admin

Access Key: Azure2026

Manage your files via the Resource Explorer or consult the AI Sidebar.

🔒 Security Note
This project uses client-side API calls for demonstration. In a production environment, it is recommended to route API calls through a secure backend or use Azure Key Vault to manage sensitive SAS tokens and API keys.

Developed for industrial cloud management and storage optimization.
