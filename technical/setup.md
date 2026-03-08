# Setup & Deployment

Open School is designed for flexibility, allowing institutions to choose the deployment model that best fits their infrastructure and security requirements.

## ☁️ Deployment Models
Choose the model that aligns with your institutional IT strategy.

### 1. On-Premise (Self-Hosted)
Deploy Open School on your own local servers for maximum control over data and security.
*   **Requirements:** Dedicated server (Linux/Windows), PostgreSQL Database, Web Server (Nginx/Apache).
*   **Best For:** Schools with existing IT infrastructure and local data governance needs.

### 2. Secure Cloud (SaaS)
Leverage our managed cloud environment for rapid deployment and zero maintenance.
*   **Requirements:** High-speed internet connection only.
*   **Benefits:** Automatic updates, daily backups, and elastic scaling.
*   **Best For:** Institutions looking to minimize local IT overhead and ensure 24/7 availability.

## 🚀 Rapid Installation Guide (Development/Testing)
For evaluation, you can set up a local instance using Docker.

1.  **Clone Repository:** `git clone https://github.com/openschool/core.git`
2.  **Configuration:** Update `env.config` with your database credentials.
3.  **Docker Compose:** Run `docker-compose up -d` to start all services.
4.  **Initial Setup:** Access the portal at `http://localhost:8080` to complete the wizard.

## 🔧 Post-Installation Checklist
*   **Organization Profile:** Set your school name, logo, and address.
*   **Role Configuration:** Define default permissions for Teachers, Parents, and Students.
*   **Email/SMS Gateway:** Configure third-party providers for automated notifications.
*   **Data Import:** Use our Excel/CSV importer for bulk student and staff entry.

---
[Technical Architecture](./features.md) | [Back to Home](../index.md)
