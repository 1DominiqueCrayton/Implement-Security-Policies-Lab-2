# Implement Security Policies — Lab 2  
## Add a Dynamic Network Zone for Allowed Countries

## Objective
Add a dynamic network zone using geographic locations.

---

## Scenario
You need to create an **Allowed Countries** network zone to use in security policies.

---

## Determine the Country You Are Signing In From

### Step 1
From the Admin Console, go to **Reports > Reports**.

<p align="center">
  <img width="1313" height="634" alt="image" src="https://github.com/user-attachments/assets/36328310-7d91-440e-bfe7-52e00f92d4ba" />
</p>

---

### Step 2
From the list of **System Log filters** on the right, select **Authentication activity**.

<p align="center">
  <img width="1313" height="634" alt="image" src="https://github.com/user-attachments/assets/2c4b2556-15e4-4955-996c-393a115b421e" />
</p>

---

### Step 3
For the top entry in the results, select the arrow to the left of the event.

<p align="center">
  <img width="1315" height="459" alt="image" src="https://github.com/user-attachments/assets/7a0babdb-9f49-4ff3-ad12-ec92e159ff09" />
</p>

---

### Step 4
Select **Expand All**.

<p align="center">
  <img width="1315" height="459" alt="image" src="https://github.com/user-attachments/assets/13113b55-92f0-43ec-b684-90ae1ce4d584" />
</p>

---

### Step 5
In the **Client** section, locate the **Country/Region** value.

<p align="center">
  <img width="1321" height="639" alt="image" src="https://github.com/user-attachments/assets/1caa31b8-bcf0-4dec-8aae-27987eb04be8" />
</p>

> **Important:** This is the country that must be added to the **Allowed Countries** network zone.

---

## Add a Dynamic Network Zone

### Step 1
Go to **Security > Networks**.

<p align="center">
  <img width="1310" height="509" alt="image" src="https://github.com/user-attachments/assets/aac24cbe-9561-451a-81ac-f6bdd2efd69d" />
</p>

---

### Step 2
Add a dynamic zone for allowed countries:

a. Select **Add Zone > Dynamic Zone**

<p align="center">
  <img width="1313" height="511" alt="image" src="https://github.com/user-attachments/assets/32ca952b-31d1-4e3c-96fe-f1811cda7642" />
</p>

b. For the **Zone name**, enter **Allowed Countries**  
c. From the **Locations** dropdown, search for and select the country identified in the System Log  
d. Do **not** select a state or region  

<p align="center">
  <img width="1331" height="564" alt="image" src="https://github.com/user-attachments/assets/75490538-e487-4380-8769-56b5ad14d007" />
</p>

e. Save the changes.

---

### Step 3
From the **Networks** page, verify that the zone is **Active**.

<p align="center">
  <img width="1313" height="561" alt="image" src="https://github.com/user-attachments/assets/b25f4e2d-be8d-4afd-9641-b3215b9e97dd" />
</p>
