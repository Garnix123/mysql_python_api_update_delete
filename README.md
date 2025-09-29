# 🗄️ Updating & Deleting Records in MySQL with Python  

## 📌 Project Overview  
This lab demonstrates how to **connect Python with MySQL**, and perform **record updates and deletions** within a relational database. The exercises highlight how to:  
- Use SQL `UPDATE` and `DELETE` queries from Python  
- Apply parameterized queries to prevent SQL injection  
- Commit changes to persist data modifications  
- Validate results using `SELECT` queries  

These are essential operations for any data professional working with transactional databases.  

---

## 🛠️ Tech Stack  
- **Python** 🐍 (mysql-connector, cursor operations)  
- **MySQL** 💾 (DML commands: `UPDATE`, `DELETE`)  
- **Jupyter Notebook** 📓  

---

## 📊 Key Learnings
✅ Always commit after INSERT, UPDATE, or DELETE to save changes
✅ Use parameterized queries (%s) to prevent SQL injection
✅ Validation with SELECT confirms that the data is updated correctly
✅ Proper cursor handling is crucial (cursor.execute(), cursor.fetchall())

---

## 💡 Business Relevance

Updating and deleting records is fundamental for maintaining data integrity in business systems:
  🏨 Hotels adjust bookings and cancellations
  🛒 E-commerce platforms update inventory or delete discontinued products
  📈 Finance systems adjust transactions while ensuring audit trails
These database manipulations directly support operational accuracy and real-time decision-making.

---
