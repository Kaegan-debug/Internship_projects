#  Shipment Management Web Form using JsonPowerDB

This project is a simple, responsive **Shipment Management Form** built using **HTML**, **Bootstrap**, and **JavaScript**, connected to **JsonPowerDB** — a fast and powerful NoSQL database. It uses the Replace API (PUT) for both saving and updating records.

---

##  Features

-  `Shipment-No` as the **Primary Key**
-  Save new shipment records
-  Update existing shipment records
-  Reset the form any time
-  Validates input fields (no empty values allowed)
-  Lightweight and works directly in your browser

---

##  Technologies Used

- HTML5 + CSS3 (via Bootstrap )
- JavaScript / jQuery
- [JsonPowerDB (JPDB)](https://login2explore.com/jpdb)
- JsonPowerDB Common JS Library



##  How It Works

1. On page load, only the `Shipment-No` input is enabled.
2. After entering a shipment number:
   - If it exists: record is displayed, `Update` is enabled.
   - If not: `Save` and rest of the form is enabled.
3. Data is stored/updated using **PUT (Replace)** API via JPDB.
4. Uses a public test token *(replace with your own in production).*



##  Test JPDB Token Used

