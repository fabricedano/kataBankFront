# BankAccount kata Front
Think of your personal bank account experience When in doubt, go for the simplest solution

# Requirements
- Deposit and Withdrawal
- Account statement (date, amount, balance)
- Statement printing
 
# User Storiess
##### US 1:
**In order to** save money  
**As a** bank client  
**I want to** make a deposit in my account  
 
##### US 2: 
**In order to** retrieve some or all of my savings  
**As a** bank client  
**I want to** make a withdrawal from my account  
 
##### US 3: 
**In order to** check my operations  
**As a** bank client  
**I want to** see the history (operation, date, amount, balance)  of my operations  


# Api Dependance with swagger ui
[bankAPINestJS](https://github.com/fabricedano/bankAPINestJS)

# Other Api Dependance
[kataBankAPI](https://github.com/fabricedano/kataBankAPI)


# Configure proxy in local developement (package?json file replace:) 

```sh
"proxy": "http://localhost:${your_server_port}",
```

# Run api
```sh
$ npm run start
```

# Run tests
```sh
$ npm run test  
```

# Run tests with coverage
```sh
$ npm run test:cov 
