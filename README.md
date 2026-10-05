# Singapore-PUB-Sharing-Calculator

A simple Windows PUB bill splitter for shared households.

This app helps calculate each person’s PUB share based on:
- 📅 Billing start and end date
- 💡 Electricity
- 🗑️ Refuse
- 🚿 Water
- 🔥 Gas
- 🧾 GST percentage
- 🏠 Room assignment
- 📆 Days present / out-of-house dates
- 👥 Tenants and visitors

---

## ✨ Features

- ✅ Auto-computes shares when values are changed
- ✅ Tenant and visitor tables
- ✅ Room column for tenants and visitors
- ✅ Calendar-based out-of-house date selection
- ✅ Computed shares table with room, days present, and final amount
- ✅ Adjustable GST dropdown
- ✅ Auto column sizing
- ✅ Simple Windows desktop app

---

## 🖥️ App Name

**Block 816 PUB Splitter**

---

## 📌 How to Use

1. 🧾 Open the app: **Block 816 PUB Splitter**.

2. 📅 Choose the **Start** and **End** date first.  
   This is very important. The app uses these dates to count the total bill days.

3. 💡 Enter the **Electricity**, **Refuse**, **Water**, and **Gas** amounts.  
   Adjust the **GST dropdown** if needed, so the **Total PUB** amount matches your actual bill.

4. 🏠 If someone was out of the house, double-click their **Out of House** column.  
   A calendar will open. Click the first day they were away, then click the last day they were away.  
   The app will highlight the days and auto-calculate their days out.

5. ✅ Check the **Computed Shares** table.  
   This shows each person’s room, days present, and final amount to pay.

---

## 🏠 Default Tenant Rooms

| Tenant | Room |
|---|---|
| Tenant 1 | Masters |
| Tenant 2 | Masters |
| Tenant 3 | Masters |
| Tenant 4 | Masters |
| Tenant 5 | Room 1 |
| Tenant 6 | Room 2 |

Visitors can also be assigned a room manually.

---

## 📆 Out-of-House Calendar

To mark someone as away:

1. Double-click the person’s **Out of House** column.
2. Click the first away date.
3. Click the last away date.
4. The app will highlight the selected date range.
5. The app will update the person’s days present automatically.

The away date range follows the selected PUB bill start and end date.

---

## 💬 Soft Reminder

Even if a tenant was out of the house during the PUB bill period, please remember that some shared or personal costs may still continue.

Wi-Fi routers still use electricity, personal fridge items still use electricity, and the standard monthly PUB refuse charge still applies.

Please discuss this kindly and fairly within your household.

---

## 🛠️ Built With

- Python
- PySide6
- PyInstaller for Windows app packaging

---

## 📄 Purpose

This app was made to make shared household PUB bill splitting easier, clearer, and more consistent.
