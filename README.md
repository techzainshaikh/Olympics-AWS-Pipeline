# 🏅 Olympics AWS Data Pipeline

A complete end-to-end **ETL pipeline project** that ingests, transforms, and uploads **Olympic Games datasets** to **Amazon S3** using **Python, Pandas**, and **Boto3**.

---

## 🚀 Features

- ✅ Extracts structured Olympic data (Athletes, Coaches, Medals, etc.)
- 🔄 Transforms data into **dimension and fact tables**
- ☁️ Uploads clean CSVs to **Amazon S3** (`s3://olympic-zn/output/`)
- 📦 Modular and production-ready ETL pipeline
- 🔐 Secure AWS integration using environment variables or direct keys

---

## 📂 Data Pipeline Architecture

┌────────────┐ ┌────────────┐ ┌────────────────┐ ┌───────────────┐
│ Raw CSVs ├────▶│ Pandas ETL │────▶│ Dim / Fact DFs │────▶│ S3 Output │
└────────────┘ └────────────┘ └────────────────┘ └───────────────┘
│
▼
s3://olympic-zn/output/


---

## 🧾 Output Tables

| File Name                    | Description                          |
|-----------------------------|--------------------------------------|
| `dimCountry.csv`            | Country-related dimension            |
| `dimAthletes.csv`           | Athlete profile details              |
| `dimCoaches.csv`            | Coach profiles                       |
| `dimMedals.csv`             | Individual medals info               |
| `dimMedals_Totals.csv`      | Country-wise medal tallies           |
| `dimTechnical_Officials.csv`| Officials info                       |
| `factOlympics.csv`          | Central fact table (joins all above) |

---

## 🛠️ Technologies Used

| Tool/Service     | Role                            |
|------------------|---------------------------------|
| **Python**       | Core language                   |
| **Pandas**       | Data manipulation               |
| **AWS S3**       | Cloud data storage              |
| **Boto3**        | AWS SDK for uploading files     |
| **Jupyter**      | Development & testing notebook  |

---




## 🙋‍♂️ About the Author

### 👨‍💻 Zain ul Abideen

📫 **Let's Connect:**
- GitHub: [github.com/techzainshaikh](https://github.com/techzainshaikh)
- LinkedIn: [linkedin.com/in/zainshaikh1](https://linkedin.com/in/zainshaikh1)
