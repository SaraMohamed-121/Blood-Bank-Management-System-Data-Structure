#Blood Donation Management System
##📋 Overview
The Blood Donation Management System is a C++ application 
designed to facilitate blood donations and requests, especially in emergency situations.
The system caters to three user roles: Donors, Recipients, and Admins,
each with distinct functionalities aimed at ensuring efficient and safe blood management.
## 🚀 Features

### 👥 Donor Features:
- **Registration**: Capture essential details:
  - ID
  - Name
  - Email
  - Password
  - Age
  - Gender
  - Blood Type
  - Health Conditions (e.g., blood pressure disorders, thyroid disease)
  - Date of Latest Donation
- **Login**: Secure system access.
- **Donation Request**: Submit requests to donate blood.
- **Data Management**: Update personal information or delete the account.

### 🏥 Recipient Features:
- **Registration**: Input necessary details:
  - ID
  - Name
  - Email
  - Password
  - Age
  - Gender
  - Blood Type
  - Hospital
  - Attending Doctor
- **Login**: Secure system access.
- **Blood Search**: Check availability of specific blood types and view details:
  - Blood Type
  - Quantity
  - Received and Expiry Dates
- **Blood Request**: Request specific blood types and quantities, with hospital confirmation.

### 🔧 Admin Features:
- **Donor Validation**: Ensure donor safety based on:
  - Age (17-60 years)
  - Last donation date (at least 3 months prior)
  - Health status (no critical conditions or medication use)
- **Inventory Management**: Manage blood stock, including:
  - Quantity
  - Received and Expiry Dates
- **User Management**: Perform CRUD operations on donor and recipient data.
- **Additional Functionalities**: Implement extra features and manage the GUI for an enhanced user experience.

## 🛠️ Technical Details

### Data Handling:
- Utilizes C++ Standard Template Library (STL) for efficient data management.

### Data Storage:
- storage through file handling (no database).
