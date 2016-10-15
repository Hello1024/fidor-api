# Fidor bank api
Fidor UK bank API to log into internet banking and get a transaction list for your current account.

## Example usage
```python
import Fidor

# Connect and login
account = Fidor.Fidor('my@email.com', 'my_password')

# List recent transactions
for tx in account.getTransactions():
  print tx

# Pay money out of my account
#account.makePayment('10.00', '220877', '36829544', 'My Ref')
```

## Todo

* Payments outbound
* Multiple accounts
