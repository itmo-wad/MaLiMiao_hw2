# MaLiMiao_hw2
## Description
<img width="1382" alt="image" src="https://github.com/user-attachments/assets/b9a4b97f-33ef-4bde-acc2-1fe057f16861" />
Login screen
<img width="1274" alt="image" src="https://github.com/user-attachments/assets/ca410f08-35e2-48b4-aa03-68dd1efaf124" />
Personal Homepage
<img width="1312" alt="image" src="https://github.com/user-attachments/assets/d3538b44-ccfb-44b9-85f0-5badc734d52a" />
Registration Page
This project is a Flask-based web application developed in Python, offering user authentication features and a customized profile page. It enables users to register accounts, log in, modify profile details, update passwords, and manage profile pictures. The backend leverages MongoDB for secure storage of user credentials, with password hashing implemented to enhance security.

## Getting Started
### Dependencies
- VScode, pycharm
- Python 3.13.2
- MongoDB Compass 7.0.16
### Executing program
```python
python app.py
```
Dataset
 open mongo service
```
brew services start mongodb-community@8.0
```
 close mongo service
```
brew services stop mongodb-community@8.0
```

Input address
```
http://127:0.0.1:5000
```

## Introduction
- Authentication Form: Users can log in via a form at http://localhost:5000/.
- Account Creation: New users can register, and upon success, are redirected to their personalized profile page.
- Password Hashing: Passwords are securely hashed before storage in MongoDB.
- Login Redirect: Successful login redirects users to their profile page at http://localhost:5000/profile.
- Profile Page: Dynamically generated for authenticated users, displaying data from MongoDB.
- Profile Information: Users can view and update personal details like name and bio.
- Profile Picture: Default image (images/profile.jpg) is assigned, with an option to upload a new one.
- Password Management: Users can change passwords post-login.
- Logout: Secure logout feature to end sessions.
- Notifications: Active users are notified of new account creations.
