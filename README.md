This app simply demos how a Stripe Payment Element can be used to collect UK bank account details and creates a BACS Direct Debit Mandate for future usage.

There is a file called .env.example which you will need to 
1. rename to .env 
2. Add your own values for Stripe API Keys etc. Add a customer ID for a customer you have already created
3. Copy the .env file into the /server folder
4. In the terminal navigate to the /server folder and run 'npm install'
5. Run 'npm start'
6. You should be able to navigate to your app locally (default is http://localhost:4242 ) and you should see a Direct Debit form
7. Fill out the form and click the disclaimer. You can use these test bank account details:
    - Sort Code: 10-88-00
    - Bank Account: 00012345
  
8. Once you have submitted the form you should see a valid direct debit payment method attached to your customer.
