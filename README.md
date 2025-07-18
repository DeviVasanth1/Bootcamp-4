# Bootcamp-4
# Real-Time Fraud Detection with Apache Beam and Google Cloud

## 🚀 Overview

This project demonstrates a real-time fraud detection pipeline using:

- **Cloud Pub/Sub** (for real-time transaction ingestion)
- **Cloud Dataflow** (Apache Beam pipeline for processing)
- **BigQuery** (for storing flagged fraud transactions)
- **Cloud Storage** (for staging/temporary data)

---

## ✅ Project Setup Summary

### 🔧 Project & Tools Used

- **Project ID:** `devi-bootcamp`
- **Service Account:** `joyuslearn@gmail.com`
- **Region:** `us-central1`
- **Environment:** Local development + Cloud deployment

---

## 📦 1. Resources Created

### ✅ Pub/Sub

- **Topic:** `fraud-transactions-topic`
- **Purpose:** Receives transaction messages in JSON format

### ✅ Cloud Storage Buckets

- **Temp bucket:** `gs://devi-bootcamp-temp-bucket`
- **Clean data bucket (optional):** `gs://devi-bootcamp-clean-data`

```bash
gcloud storage buckets create gs://devi-bootcamp-temp-bucket --location=us-central1
