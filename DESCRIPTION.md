
## 📊 Dataset Description: Fintech Transactions

This dataset contains anonymized records of customer financial transactions for a fintech platform. Each row represents a single transaction, including details about the customer, transaction type, status, and metadata.

### 🔑 Key Fields

| Column Name       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `Transaction_ID`  | Unique identifier for each transaction (e.g., T100001)                     |
| `Customer_Name`   | Customer’s first name                                                       |
| `Date`            | Transaction date in the format `YYYY-MM-DD`                                |
| `Amount`          | Transaction amount in numeric format (float)                               |
| `Currency`        | Currency code in ISO format (e.g., USD, EUR, INR)                          |
| `Merchant`        | Merchant name where the transaction occurred (e.g., Amazon, Apple)         |
| `Category`        | Transaction category (e.g., Travel, Utilities, Food)                       |
| `Payment_Method`  | Payment mode used (e.g., Debit Card, UPI, Bank Transfer)                   |
| `Status`          | Status of the transaction (Completed, Pending, Failed, Cancelled)          |
| `Country`         | Country where the transaction was made (e.g., United States, Germany)      |

### 📌 Data Characteristics

- Total Rows (after cleaning): Depends on removal of null values  
- Missing values: Removed in final cleaned version  
- All fields are standardized for easy analysis or ingestion into machine learning pipelines  
