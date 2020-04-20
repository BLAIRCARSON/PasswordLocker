# Password Locker

## Author

- Kirui Vincent

## Description

- Password locker enables users to create, store,change and/or retrieve their login credentials of different accounts

## Technoligies used

- python 

## Features


As a user of the terminal application you will be able to:

1. Create an account
2. Log into your account
3. Add credentials for different accounts
4. Store and generate passwords
5. See a list of all your saved credentials
6. Search for a saved credential
7. Copy credentials to the clipboard
8. Delete a saved credential

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display codes for navigation | *In terminal: $./run.py* | Welcome, choose an option: cc-Create Account, li-Log In, ex-Exit |
| Display prompt for creating an account | *Enter: cc* | Enter your first name, last name and password |
| Display prompt for login in | *Enter:* | Enter your account name and password |
| Display codes for navigation | *Successful login* | Choose an option: cc - Create Credential, dc - Display Credentials, fc - Find Credential, ex - exit |
| Display prompt for creating a credential | *Enter: cc* | Enter the site name, your username and password |
| Display a list of credentials | *Enter: dc* | Prints a list of saved credentials |
| Find a credential | *Enter: fc* | Prints the searched credential |
| Display prompt for which credential to copy | *Enter: cp* | Enter the site name of the credential you wish to copy. |
| Deletes a saved credential | *Enter: del* | Prints success |
| Exit application | *Enter: ex* | Exit the current navigation stage |

 
## Getting started
### Prerequisites
* python3.6
* pip
* pyperclip
* xclip

### Cloning
* In your terminal:
        
        $ git clone https://github.com/BLAIRCARSON/PasswordLocker
        $ cd Password

## Running the Application
* To run the application, in your terminal:

        $ chmod +x run.py
        $ ./run.py
        
## Testing the Application
* To run the tests for the class file:

        $ python3.6 user_password_test.py
        

## Contacts & Support

- engineervinceblair@gmail.com

## License

- License under <a href="https://github.com/BLAIRCARSON/PasswordLocker/blob/master/LICENSE">MIT LICENSE</a>