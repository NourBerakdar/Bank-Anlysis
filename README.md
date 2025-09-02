# Bank Analysis  

Helping managers understand customers and their financial behavior to make better decisions.  

## 📌 Overview  
This project provides an analysis of **Jordan Bank** customer data through interactive dashboards.  
The main objectives are:  
- Understand customers and their financial/behavioral patterns.  
- Analyze spending habits and compare customer segments.  
- Assess risks and support data-driven decision making.  

## 📊 Dashboards  
The project contains three main dashboards:  
1. **Overview** – A general look at the datasets.  
2. **Users & Cards** – Analysis of customers along with their credit/debit card details.  
3. **Transactions** – Analysis of financial transactions and spending behavior.  

## 🗂️ Data Description  
The dataset consists of three interconnected tables providing a holistic view of customers and their financial behavior:  

### 1. Transactions Data (`transactions.xlsx`)  
Captures all financial transactions performed by customers:  
- `id`: Unique transaction ID  
- `date`: Transaction date  
- `client_id`: Customer ID  
- `card_id`: Card ID used  
- `amount`: Transaction amount  
- `use_chip`: Whether a chip was used (Yes/No)  
- `merchant_id`: Merchant ID  
- `merchant_city / state / zip`: Merchant location  
- `mcc`: Merchant Category Code (business type)  
- `errors`: Errors encountered (failed/declined payments)  

---

### 2. Cards Data (`cards_data.xlsx`)  
Details of the customer’s issued bank cards:  
- `id`: Card ID  
- `client_id`: Customer ID  
- `card_brand`: Card brand (Visa, MasterCard, etc.)  
- `card_type`: Type (Credit, Debit, Prepaid)  
- `credit_limit`: Credit limit assigned  
- `acct_open_date`: Account opening date  
- `year_pin_last_changed`: Last PIN update year  
- `card_on_dark_web`: Whether card was detected on the dark web  

---

### 3. Users Data (`users_data.csv`)  
Customer identity and personal/financial information:  
- `id`: Customer ID  
- `current_age`: Current age  
- `yearly_income`: Yearly income  
- `total_debt`: Total debt  
- `credit_score`: Credit score  
- `num_credit_cards`: Number of credit cards owned  
- `gender`: Gender  
- `address, latitude, longitude`: Residence location  

---

## 📌 Summary  
- **Users Data** → Customer identity and demographics.  
- **Cards Data** → Financial details and credit records.  
- **Transactions Data** → How customers use their cards and where they spend.  

By combining these datasets, we can:  
✔️ Analyze spending behavior  
✔️ Assess risks  
✔️ Support strategic financial decisions  

---

## 📈 Insights from Analysis  
This work was conducted during the **DataDrip Hackathon** with **Team Qafza**, which brought together participants from across the Arab world.  

✨Key findings from the dashboards include:  
1. The proportion of users under 20 years old was significantly higher compared to other age groups.  
2. Debts were particularly high among **Credit Card holders**, with around **57%** having notable debt levels.  
3. More than **12 million failed transactions** were recorded — an issue that requires deeper investigation.  

---

## 📎 Tags  
#DataAnalysis #Banking #Dashboard #Jordan #AI #DataDrip #Qafza  
