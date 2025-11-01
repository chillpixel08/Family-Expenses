# Family-Expenses
Naan Mudhalvan project

# Calculating Family Expenses
💰 Family Finance Tracker on ServiceNow: Project Summary
Goal
To create a comprehensive, scalable system on ServiceNow for families to track, categorize, and manage their expenses efficiently, promoting informed financial decisions.

Core Functionality
Dual-Table Structure:
Family Expenses: The main parent table for expense summaries.
Daily Expenses: The child table for individual transaction details (who, what, when).
Automated Data Integrity:
A Business Rule ensures the main Family Expenses record is automatically updated (total amount, details) whenever a new or modified daily expense is logged.
Sequential Auto-Numbering (MFE prefix) for both tables ensures clean record IDs.
Intelligent Relationship:
The two tables are linked, and a related list query ensures that only the relevant daily entries (matching by date) are displayed on the parent form.
Key Development Highlights
Setup: Secured a PDI and created the "Family Expenses" Update Set.
Design: Configured forms with mandatory fields (Date, Amount, Family Member Name) and read-only fields (Number).
Access: Created a dedicated "Family Expenditure" menu for easy user navigation.

and below attached medias contains the process of the whole project which include the photo and the images<br>

https://github.com/user-attachments/assets/26056a45-dc84-4c0b-9a13-d9eea2b61764

![project ss (19)](https://github.com/user-attachments/assets/52ee0996-f342-4cce-a33e-63985ce1ee12)
![project ss (18)](https://github.com/user-attachments/assets/d4336a4d-b795-4b9a-ab3d-54d470274ae9)
![project ss (17)](https://github.com/user-attachments/assets/55320d97-aacd-452e-a927-5a9715039a29)
![project ss (16)](https://github.com/user-attachments/assets/8fa3e8ad-88ba-463a-98c0-cc424c6d8b5a)
![project ss (15)](https://github.com/user-attachments/assets/a7c2f2dd-b149-4c20-afd2-9ace4e8abbde)
![project ss (14)](https://github.com/user-attachments/assets/c12a5c19-74e6-46b4-ac26-38ac89d386f9)
![project ss (13)](https://github.com/user-attachments/assets/f39ac990-565e-46aa-8934-e528c510acca)
![project ss (12)](https://github.com/user-attachments/assets/396e9411-4bec-4583-97a8-a32d50253c29)
![project ss (11)](https://github.com/user-attachments/assets/3f6f6e98-f018-4708-87fd-9f567190addd)
![project ss (10)](https://github.com/user-attachments/assets/6afbde03-aa98-43c5-b472-d257d4718ab1)
![project ss (9)](https://github.com/user-attachments/assets/44e74015-0bc8-4ea9-ae59-e62a983e6778)
![project ss (8)](https://github.com/user-attachments/assets/cb8be0f5-b07d-41c2-86ca-a02e4c2e29b0)
![project ss (7)](https://github.com/user-attachments/assets/836185de-e16b-4e12-adcc-eac8086d1cc9)
![project ss (6)](https://github.com/user-attachments/assets/1ba6ce7d-4a8f-4968-ac42-3a38a5f1781a)
![project ss (5)](https://github.com/user-attachments/assets/5b76c810-2c82-4786-a444-2e4eba46fc86)
![project ss (4)](https://github.com/user-attachments/assets/2959b569-f117-4ba7-a7d0-68138ae88e2e)
![project ss (3)](https://github.com/user-attachments/assets/0006c570-9778-4270-b5fb-445e3efd9f2f)
![project ss (2)](https://github.com/user-attachments/assets/5927cd95-1e3c-47d8-8430-67d5ff8168fe)
![project ss (1)](https://github.com/user-attachments/assets/95e00335-e5a5-4721-b922-1e8c27af0003)

The below link is the pdf of our report on Calculating family expenses<br>
[Calculating-Family-Expenses-using-ServiceNow (1) (1).pdf](https://github.com/user-attachments/files/23280661/Calculating-Family-Expenses-using-ServiceNow.1.1.pdf)

✅ Conclusion

This project successfully demonstrates a Family Expense Calculation System built on ServiceNow.
It records daily expenses, calculates totals automatically, and provides clear report views.
By automating expense tracking, this project simplifies financial monitoring for families.


Our Team Name:
AKASH KUMAR( TEAM LEADER )<br>
DEEPAK KUMAR BIND</br>
GURAPNOOR SHARON CHITHMABER</br>
 Department: Computer Science and Engineering (CSE)
 College: Grace College of Engineering, Thoothukudi
