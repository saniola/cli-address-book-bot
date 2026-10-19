# CLI Address Book Bot

A command-line assistant bot for managing contacts, their phone numbers, and birthdays.

## Features

- Add, change, and look up a contact's phone number
- Add and show a contact's birthday
- List contacts with birthdays occurring in the upcoming week
- Input validation for phone numbers and birthdays

## Commands

- `add [name] [phone]` — add a new contact with a name and phone number
- `change [name] [old phone] [new phone]` — change the phone number for a contact
- `phone [name]` — show the phone number for a contact
- `all` — show all contacts
- `add-birthday [name] [birth date]` — add a date of birth for a contact
- `show-birthday [name]` — show the date of birth for a contact
- `birthdays` — show birthdays occurring in the next week
- `hello` — get a greeting from the bot
- `close` or `exit` — close the program

## Technology

- Python 3 (standard library only)

## Project structure

```
main.py                    Entry point
app.py                     Command loop
adressbook.py               AddressBook class
record.py                  Record class
field.py / name.py / phone.py / birthday.py   Contact field classes
decorators/input_error.py  Error-handling decorator
utils/                     Command handlers and helper functions
```

## Running

```
python main.py
```
