---
layout: page
title: "Production Real-Time Food Delivery Ecosystem"
description: "Full-stack real-time platform with Apollo Server 4 GraphQL microservices, React 19 web ordering client, and React Native / Expo SDK 53 cross-platform mobile apps."
importance: 1
category: "Full-Stack"
related_publications: false
---

# Real-Time Food Delivery Ecosystem & Apollo GraphQL Platform

**Stack:** Node.js, Express, Apollo Server 4, GraphQL, WebSockets (`graphql-ws`), MongoDB, React 19, Vite, Tailwind CSS v4, React Native, Expo SDK 53, TypeScript, Apollo Client, Cloudinary, JWT, RBAC

---

## Overview

A production-grade, multi-client real-time ordering and fulfillment ecosystem consisting of an Apollo GraphQL microservice, single-page web ordering portal, and specialized customer and store-manager mobile applications.

---

## Architecture & Components

* **Real-Time Backend (`restaurant-apollo-backend`):**
  * Engineered a decoupled GraphQL microservice with Apollo Server 4 and MongoDB.
  * Implemented real-time WebSocket subscriptions (`graphql-ws`, Pub/Sub) providing instant notification dispatch (`NEW_ORDER_ADDED`) to kitchen and operations dashboards with sub-second latency.
  * Role-based access control (RBAC) middleware across `ADMIN`, `MANAGER`, `STAFF`, and `CUSTOMER` roles secured with JWT and bcrypt.
* **Customer Mobile App (`UserFrontendRestaurantNative`):**
  * Built using **React Native**, **Expo Router**, and **TypeScript**.
  * Features persistent cart management, dynamic hero banners, order history tracking, and bilingual localization (English / Urdu).
* **Manager Operations App (`RestaurantFrontendNative`):**
  * Live order transition queue (Pending $\rightarrow$ Preparing $\rightarrow$ Out for Delivery $\rightarrow$ Completed).
  * Multipart image uploads directly to Cloudinary CDN via `apollo-upload-client`.
* **Responsive Web Ordering Portal (`restaurant-app-web-frontend`):**
  * Built with **React 19**, **Vite**, and **Tailwind CSS v4**.
  * Includes client-side localization dictionary and robust checkout validation pipelines.

