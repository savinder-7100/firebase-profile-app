# firebase-profile-app

Parts of the project explained: 

1) Authentication - Authentication is done in two ways, first is standard email and password authentication and second is social networking site authentication. The registered user (registered by any mean) entries can be checked in the Authentication section of the Firebase console.

2) Firebase Database - Once the user is signed in, we are using his/her's details and storing them in the firebase database. Later on (on the account page), we are showing them as the user's account profile. The values we are capturing is email, FIrst Name, Last Name, and profile picture.

3) Firebase Storage - For customer registered via email id and password, no profile picture can be fetched from the user's profile. Hence we are uploading the image in this case. The uploaded image is stored in the firebase database.