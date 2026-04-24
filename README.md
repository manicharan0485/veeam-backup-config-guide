# 🛡️ Veeam Backup & Replication — Configuration Guide

Practical configuration guides, best practices, and example job configurations for Veeam Backup & Replication in hybrid and cloud-connected environments.

---

## 📁 Repository Structure

```
veeam-backup-config-guide/
├── guides/
│   ├── 01_job_configuration_best_practices.md
│   ├── 02_retention_policies.md
│   └── 03_application_aware_backup.md
├── examples/
│   └── backup_job_config_examples.md
└── README.md
```

---

## 📌 Key Topics Covered

- ✅ Backup job types (Full, Incremental, Reverse Incremental)
- ✅ Proxy server setup and sizing
- ✅ Retention policy design (GFS — Grandfather-Father-Son)
- ✅ Application-aware processing (VSS, transaction log truncation)
- ✅ Instant VM recovery
- ✅ Restore types (file-level, VM-level, application-level)
- ✅ Backup copy jobs for offsite / cloud DR
- ✅ Encryption configuration

---

## 🔧 Environment

- Veeam Backup & Replication v12
- VMware vSphere / Hyper-V
- Windows Server 2019/2022
- Integration: AWS S3 (Scale-out Backup Repository), Azure Blob

---

## 👤 Author

**Manicharan Ravi** — IT Specialist & Cloud Engineer  
📧 manicharan.ravi999@gmail.com  
🔗 [linkedin.com/in/manicharan-ravi](https://linkedin.com/in/manicharan-ravi)
