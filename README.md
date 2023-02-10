### All(4) iteration documentation and form application screenshots can be found [here](https://docs.google.com/document/d/11n-ew8yiJiHotcpuk0ATZNpT67K25RMHbYG_5k01SG4/edit?usp=sharing)


# Overview (Boring C# Project)
Hog Bank is a local bank that serves students and locals. As a recent U of A undergrad who started Hog Bank, the business model has been that of a traditional bank – customers can deposit and withdraw from the location or online.  They can also sign up for various investing opportunities or loan opportunities. To support the operations, Hog Bank used a “hosted” Point-of-Sale (POS) system which tracked basic customer account information, investment and loan data, and transactions.  After several months of effort to make the business profitable, Hog Bank has decided that they need to try something new. You have been hired as the consulting team to develop a new and exciting interface for Hog Bank.




# Buisness Problem
As your liaison to Hog Bank, I will be your point of contact as you develop a solution to help grow Hog Bank into a great company and even more progressive business models.
What we have to work with is:
- Ownership of 1 physical store in Fayetteville.
- The lease for building is $2,000 per month.  This expense needs to be tracked in order to determine if a profit is being made.
- A staff of 5 people that work for the company (4 tellers and a bank branch manager) for a total cost of around $7,200/month.
- Overhead, bookkeeping, etc. has been roughly 10% of their total expenses thus far, but needs to be tracked more appropriately.
- We have to keep track of inventory (cash) and all updates to ensure that things are kept in regulation. 
- Around 2,500 customers frequent the location. These customers have a variety of needs.    

At this point, the direction for Hog Bank is in your hands. I have enlisted your team to help me figure out the answers to two very important questions:
- How do I take what I have and turn Hog Bank into a more competitive and economically feasible business?
- What sort of system do I need to support the new business?  




# System / Data Req.
The following information, at a minimum, will be required in order to create, maintain and track important components of the banking business.  Depending on the proposed model, more components (both entities and attributes) will almost certainly need to be introduced.  
- Customer: Customer Id, first & last name, address (for mailings), phone numbers, e-mail address, status (Juicy perks, inactive, guest), join date, other authorized users on the account, etc.
- Building: Building number, Branch name, address, phone number, e-mail, contact person, web site, etc.
- Employee: Employee Id, first & last name, address, phone numbers, e-mail address, status (current, terminated, etc.), type, hourly rate, hire date, etc.
- Accounts: Account_ID, balance
- Loans: Loan_Id, Name, Type, Cost, Interest, Balance
- Investments: Investment_ID, Name, Type, Current_Balance, Interest




# System Req.
The system that you develop in this class will need to include, at a minimum:
- Operational requirements
- Add/edit/delete customers
- Add/edit/delete investments and/or accounts
- Add/edit/delete employees
- Reporting
- Generate a loans and investments report
- Generate a basic customer profile
- Employee reports (Hires, terminations, etc.)




