# Email Simulator 📧

A Python-based **Email Simulator** that demonstrates object-oriented programming concepts by simulating basic email operations between users.

## 📌 Features

* Create users with individual inboxes
* Send emails between users
* Receive and store emails
* Display inbox emails
* Read individual emails
* Automatically mark emails as read
* Delete emails
* Display email timestamps
* Show email status as Read/Unread
* Display formatted email details
* Provide confirmation messages when emails are sent or deleted

## 🛠️ Concepts Used

This project demonstrates several Python and Object-Oriented Programming concepts:

* Classes and Objects
* Constructors (`__init__`)
* Instance Attributes
* Instance Methods
* Encapsulation
* Lists
* Conditional Statements
* `for` Loops
* `enumerate()`
* String Formatting with f-strings
* `__str__()` Method
* `datetime` Module
* Index Validation
* Python Main Guard

## 📂 Project Structure

```text
email-simulator-python/
│
├── email_simulator.py
└── README.md
```

## 🚀 How It Works

The simulator creates users and allows them to communicate through email objects.

For example:

```python
tory = User("Tory")
ramy = User("Ramy")

tory.send_email(ramy, "Hello", "Hi Ramy, just saying hello!")
ramy.send_email(tory, "Re: Hello", "Hi Tory, hope you are fine.")
```

Users can then:

```python
ramy.check_inbox()
ramy.read_email(1)
ramy.delete_email(1)
```

## 🎯 Purpose

This project was created as a practical exercise to strengthen Python programming and object-oriented programming skills through a simple real-world simulation.


