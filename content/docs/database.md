---
weight: 500
title: "Database: MonogDB"
description: "Fully Database Support for storing Users, Owner settings and files."
author: "SilentDemonSD"
icon: database
draft: false
---

# **MongoDB Database Creation Guide**

This guide walks you through creating a MongoDB database in the simplest way possible.

---

## **Step 1: Access MongoDB**
1. Open the [MongoDB website](https://www.mongodb.com/).
2. Sign in or create a free account.

---

## **Step 2: Set Up a Cluster**
1. Go to the **Atlas** section after logging in.
2. Click **Create a Cluster**.
3. Choose a free tier (Shared Cluster) and your preferred cloud provider (e.g., AWS, GCP, or Azure).
4. Select your region for optimal performance.
5. Click **Create Cluster**.

---

## **Step 3: Create a Database**
1. Once your cluster is ready, click **Browse Collections** in the cluster dashboard.
2. Click **Add My Own Data**.
3. Enter a **Database Name** (e.g., `wzmlx-db`).
4. Enter a **Collection Name** (e.g., `users` or `posts`).
5. Click **Create**.

---

## **Step 4: Allow Access from Anywhere**
1. Go to the **Network Access** tab in the MongoDB Atlas dashboard.
2. Click **Add IP Address**.
3. To allow access from anywhere, click **Allow Access from Anywhere** (or add `0.0.0.0/0` as the IP address).
4. Click **Confirm**. This will grant permission for any IP to connect to your MongoDB database.

---

## **Step 5: Connect to the Database**
1. In your cluster dashboard, click **Connect**.
2. Choose a connection method:
   - **Connect your application** (recommended for Wzmlx integration).
   - Copy the connection string (e.g., `mongodb+srv://<username>:<password>@cluster0.mongodb.net/wzmlx-db`).
3. Replace `<username>`, `<password>`, and `wzmlx-db` with your credentials.

---

## **Step 6: Use the Database**
1. In your project directory, find the file named **`Config.env`**
2. Open the `Config.env` file and add the MongoDB connection string like this:

   ```
   MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/wzmlx-db
   ```

   Replace `<username>`, `<password>`, and `wzmlx-db` with your actual MongoDB credentials and database name.

---

## **Step 7: Run the Application**
1. Now, when you run your application, it will automatically connect to MongoDB using the URI specified in your `Config.env` file.
