# Project description
This is a small web project that works as an online banking system which allows the user to perform the following tasks:
  1. Deposit
  2. Withdraw
  3. Transfer
  4. View transactions

### 1. Deposit

This is a form that requires for the user to provide some details, like the bank account, amount and reason for the transaction.
It also come with some validation, like the reason should be a string of no less than 10 character, amount should be  1000 and above and finally same transaction can't be submitted over and over again, the user should at least modify the reason to avoid redundancy.

### 2. Withdraw

This is also a form that asks for a few details, like the bank account, amount and reason for the transaction.
Like the Deposit form, this one comes with some validation as well. Like the bank account provided by the user must be must be pre-registered in the system, the user can not Withdraw amount that is more than the current balance and finally same transaction can not be repeated to avoid redundancy.

#### 3. Transfer

This is a form that requires some basic information in order for the Transfer to happen, like source account, description account and amount to Transfer and a reason.
This comes with some validations as well, like both account must exist in the system, user can not transfer an amount that is more than current balance,same transaction can not be repeated to avoid redundancy.


## View transactions

This is just a table that shows all transactions of all sorts.

# About technology used
        1. HTML5/CSS3
        2. jQuery
        3. scss
        4. Servlet
        5. JSP
        6. HIBERNATE
        7. MYSQL
        8. Bootstrap

## More on bootstrap

Bootstrap is framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2019  . Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-freelancer/blob/gh-pages/LICENSE) license.
