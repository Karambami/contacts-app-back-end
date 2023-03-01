# Contacts app developed with Python

This is a simple contact management app written in Phyton programming language.

To develop this app we have used the following programming elements:

- functions
- json module
- file input/output (write/read)


```py
import json

contacts = []

def AddContact():
    name = input("Enter name: ")
    surname = input("Enter surname: ")
    phone = input("Enter phone: ")
    email = input("Enter email: ")

    contact = {
        'name': name,
        'surname': surname,
        'phone': phone,
        'email': email
    }

    contacts.append(contact)
