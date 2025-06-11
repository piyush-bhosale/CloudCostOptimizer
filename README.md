# 🌐 Cloud Cost Optimizer – Multi-Cloud Cost Comparison Tool

**Cloud Cost Optimizer** is a lightweight, extensible tool that helps engineers, architects, and businesses compare cloud costs across **AWS**, **Azure**, and **Google Cloud Platform (GCP)** for key resources: **compute (VMs/instances), storage, and managed databases**.

---

## 🎯 Objective

To provide a side-by-side comparison of cloud resource pricing based on user-defined specifications like region, instance type, storage size, and database engine — helping teams choose the most cost-effective cloud provider.

---

## 📊 Key Features

- 🖥️ **Compute Cost Comparison**  
  Compare virtual machine (EC2, Azure VM, GCE) pricing by vCPU, RAM, region, and OS.

- 💾 **Storage Cost Comparison**  
  Analyze S3 vs Azure Blob vs GCP Cloud Storage by size, access pattern, and redundancy.

- 🗄️ **Database Cost Comparison**  
  Compare pricing for managed databases (RDS, Azure SQL, Cloud SQL) by engine, size, and region.

- 🌍 **Region-Based Pricing**  
  View cost impact based on region selection.

---

## 📝 Example Output (Optional)

| Resource | AWS        | Azure      | GCP        |
|----------|------------|------------|------------|
| Compute  | $75/month  | $78/month  | $72/month  |
| Storage  | $9.20      | $10.50     | $8.80      |
| Database | $150/month | $162/month | $145/month |

---

## 🚀 Coming Soon

- Real-time pricing via cloud cost APIs
- CSV/PDF export of comparison reports
- CLI tool and web UI
- ROI calculator for reserved/spot pricing

---

## 📂 How to Use

1. Clone the repo.
2. Fill `input.yaml` or `.json` config file with desired specs.
3. Run the comparison engine.
4. View the report on terminal or export to file.

---

## 📄 License

This project is licensed under the MIT License – see the `LICENSE` file for details.

---

