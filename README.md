JUST run the <<main.py>>
otherwise it not gonna work correctly!!!

This repository provides a robust and secure solution for user authentication. It ensures that user passwords are hashed using standard algorithms, safeguarding sensitive information. Here are the key features:

1. Password Hashing: User passwords are transformed into irreversible hashes, preventing unauthorized access even if the hashed passwords are exposed.
2. Cryptographically Random Salt: Each password hash is salted with a unique value, enhancing security against rainbow table attacks.
3. Peer-Reviewed Libraries: This library use the bcrypt algorithm with a high number of iterations to protect passwords.


***after run <<main.py>> you will see some options: ***

1. sign in: this will add users and hashed password(with bcrypt) into data base.
2. sign up: this will ask username and password from user and check if it's correct.

just be careful that it is sensitive to spaces so don not type any un wanted space in  it when you are using it 

and pleas read the requirements file ...

this is a sample program for manage users sign in and out.
it will save usernames and passwords  in to a database(sqlite)*the passwords will be save completely safe and hashed with salt*

This repository contains the source code for the user_manager. You can clone the repository and run the code on your local machine.

Feel free to contribute to the project by submitting pull requests or reporting issues. Your contributions are greatly appreciated!

