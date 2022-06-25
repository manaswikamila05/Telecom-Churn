# :satellite: Telecom Customer Churn Case Study using SQL, Python and Tableau



# :pushpin: Problem Statement

- You are working as an analyst in a telecom company that provides home phone and internet services to 7,043 customers across Southern California.
- A new competitor has moved into the area, and the company you are working for is concerned about losing its existing customers.
- Your company decided to dig deeper into what is casuing customers to leave the company.

# :dart: Business objectives
The senior management of your company has defined the business objectives listed below, and it wants you to offer suggestions that can help achieve these objectives:
- Understand which services provided by the company are not performing well, so that the product team can improve the quality of such services and ensure the existing customers are happy with them.
- Identify which variables are affecting the customers’ churn, based on existing data.
- Identify the services that are being received well by the customers so that the company can use them to attract new customers.
- Identify high-value customers so that the company can provide them with a premium membership to retain them for as long as possible.

# :information_source: Data exploration
- customer.csv

![image](https://user-images.githubusercontent.com/77529445/174257963-a73f86cd-ff43-4d58-b2e0-354f623f99eb.png)

- cust_loc.csv

![image](https://user-images.githubusercontent.com/77529445/174258132-e21045bf-ab17-4592-b79d-87f771a621c2.png)

- cust_account.csv

![image](https://user-images.githubusercontent.com/77529445/174258220-5c68f30c-f68b-4815-9435-6a0c35e375f2.png)

- cust_services.csv

![image](https://user-images.githubusercontent.com/77529445/174258357-2e611f15-cec7-4baa-b12c-54bef3f43ed0.png)

- cust_churn.csv

![image](https://user-images.githubusercontent.com/77529445/174258435-8ff4b04f-8a8f-4515-9de5-6141ca3dea44.png)

ERD diagram

![image](https://user-images.githubusercontent.com/77529445/174948366-c3156dae-bb82-4b08-b831-38978e81a0f2.png)

The database satisfies all normalization up to the third normal form.

# :bookmark: Key metrics
### Customer churn
Customer churn can be defined formally as the percentage of customers who have discontinued their subscription to a service in a given period of time. 
Churn rate = (Number of customers lost) /(Total customers started with)

Why is customer churn important?
- It is less expensive to retain customers than to attract new customers.
- Customer churn helps competitors
- Existing customers when statisfied, are an excellent source for brand promotions.
- Higher churn rate is an indicator of a bigger company problem.

Reasons for customer churn
- Customer service
- Quality
- Price
- Functionality
- Convienience
- Needs changed

### Customer lifetime value (CLV)
Customer lifetime value (CLV) is the net profit associated with a customer for a company over a fixed period of time. A customer with a high CLV is an indicator of recurring revenue, and companies are willing to take measures to retain such customers for as long as possible.

Why is Customer lifetime value important?
- Higher ROI
- Higher Customer lifetime value, less likely to churn
- Custom-made customer programs to improve memberships

# :memo: Approach
![image](https://user-images.githubusercontent.com/77529445/174260569-99155d66-6090-4f94-9967-ac607b801f19.png)

# :pick: Tools used
- SQLite
- Python
- Tableau

# :bar_chart: Visualization
Produced a Tableau story.

Tableau: [Telecom Customer Churn](https://public.tableau.com/app/profile/manaswi.kamila/viz/TelecomCustomerChurnAnalysis_16561435637710/TelecomCustomerChurnAnalysis)
