---
layout: page
title: "Healthcare Point of Sale & AWS Cloud Architecture"
description: "Cloud-native healthcare POS and inventory microservice featuring AWS S3 streaming upload pipelines, MongoDB aggregations, and 5-tier role authorization."
importance: 2
category: "Full-Stack"
related_publications: false
---

# Healthcare Point of Sale & AWS Cloud Architecture

**Stack:** Node.js, Express, Apollo Server Express, GraphQL, MongoDB, Mongoose, AWS SDK v3 (S3 streaming), Cloudinary, JWT, RBAC

---

## Overview

A robust commercial healthcare point-of-sale (POS) and inventory backend engineered for automated medical store operations, prescription verification, and comprehensive financial ledger accounting.

---

## Technical Highlights

* **AWS S3 Streaming Storage Pipeline:** Implemented resilient cloud storage with AWS SDK v3 (`@aws-sdk/client-s3` and `@aws-sdk/lib-storage`), streaming prescription documents and medication product photography directly to S3 buckets with UUID key resolution.
* **Complex Aggregation Pipelines:** Authored high-performance MongoDB aggregation pipelines (`$match`, `$group`, `$sort`, `$dateToString`, `$sum`) powering real-time daily/weekly sales analytics, category margin tracking, and inventory turnover reports.
* **Transactional Invoicing & POS Logic:** Engineered sales resolvers managing line items, barcode queries, automated inventory deductions, and customizable receipt printing.
* **Patient Credit Ledger:** Dedicated balance-tracking subsystem managing accounts receivable and payment reconciliation for recurring patients.
* **5-Tier Role Authorization:** Fine-grained healthcare RBAC safeguarding clinical and transactional data across `ADMIN`, `PHARMACIST`, `STAFF`, `MANAGER`, and `CUSTOMER`.

