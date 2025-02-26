# MaLiMiao_hw2
## Description
<img width="1382" alt="image" src="https://github.com/user-attachments/assets/b9a4b97f-33ef-4bde-acc2-1fe057f16861" />
Login screen.
<img width="1274" alt="image" src="https://github.com/user-attachments/assets/ca410f08-35e2-48b4-aa03-68dd1efaf124" />
Personal Homepage.
<img width="1365" alt="image" src="https://github.com/user-attachments/assets/2f42dadc-ca82-495b-a69f-39878a285bff" />
Update personal homepage.
<img width="1378" alt="image" src="https://github.com/user-attachments/assets/a0f6e31a-7a29-42a9-8a85-7d51ff246ee8" />
change password.
<img width="1312" alt="image" src="https://github.com/user-attachments/assets/d3538b44-ccfb-44b9-85f0-5badc734d52a" />
Registration Page（Here users can enter their own information, select their own personal skills, upload photos, etc.）
<img width="1425" alt="image" src="https://github.com/user-attachments/assets/94db922a-dde0-42f4-83f7-fda4329bb437" />
User data is stored in the database.
This project is a Flask-based web application developed in Python, offering user authentication features and a customized profile page. It enables users to register accounts, log in, modify profile details, update passwords, and manage profile pictures. The backend leverages MongoDB for secure storage of user credentials, with password hashing implemented to enhance security.

## Getting Started
### Dependencies
- VScode, pycharm
- Python 3.13.2
- MongoDB Compass 7.0.16
### Run the application
python
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
Visit http://127.0.0.1:5000/ to view the profile page.
