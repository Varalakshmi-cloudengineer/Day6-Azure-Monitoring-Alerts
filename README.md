 # Day 6 - Azure Monitoring and Alert Rule Project

This project demonstrates how to configure **Azure Monitoring** by creating an **alert rule** that triggers based on **CPU usage** of a virtual machine.

---

## 🛠️ Azure Resources Created

- **Resource Group:** monitoring-rg  
- **Virtual Machine Name:** monvm01  
- **OS:** Ubuntu 22.04 LTS  
- **Monitoring Tool:** Azure Monitor  
- **Alert Type:** CPU Percentage > 80% for 5 minutes  
- **Notification:** Email via Action Group (mon-alert-group)

---

## 🔔 What I Did

- Created a temporary VM to simulate monitoring
- Used Azure Monitor to set up an alert for high CPU usage
- Created an Action Group to send email notifications
- Verified that the alert rule was listed under active monitoring

---

## 📘 Learnings

- How to monitor Azure VM performance using metrics
- How to set CPU-based alert thresholds
- Importance of Action Groups for automated notifications
- Best practices for resource cleanup to save cost

---

## ✅ Cleanup

Deleted VM and monitoring resources to avoid charges after testing.

---

## 👩‍💻 Author

**Varalakshmi**  
Cloud Support Engineer | Azure & AWS Enthusiast  
GitHub: [Varalakshmi-cloudengineer](https://github.com/Varalakshmi-cloudengineer)
