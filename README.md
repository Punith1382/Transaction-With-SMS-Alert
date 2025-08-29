# Bank Account System with SMS Notifications

This project is a **Python-based Bank Account simulation** that integrates with **Twilio SMS API**.  
It allows deposit and withdrawal operations, while sending SMS alerts for each transaction.

---

## Features

- **Custom Exception Handling**
  - Uses `InvalidAccountError` for invalid operations (e.g., insufficient balance, invalid deposit).

- **BankAccount Class**
  - `withdraw(amount)` → Withdraws funds, validates balance, sends SMS alert.
  - `deposit(amount)` → Deposits funds if amount is positive, sends SMS alert.
  - `send_sms(message)` → Sends transaction notifications via Twilio.

- **Twilio Integration**
  - Uses Twilio REST API to send SMS.
  - Requires `account_sid`, `auth_token`, and a Twilio phone number.

---

