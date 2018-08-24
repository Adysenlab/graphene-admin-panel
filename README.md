# Graphene admin panel

@graphene is a spinoff from adysenlab for partner companies

Simple Firebase Admin Server using NodeJS.

with the growth of requirement in Web apps We are releasing a test compile for the sample firebase product that we have built with love.

> Have existing express server? Try out [Express Firebase Middleware](https://github.com/antonybudianto/express-firebase-middleware)

## How to use
1. Clone this repo and change directory to the cloned folder
2. Install the packages

   ```sh
   npm install
   ```

3. You need to download your Firebase Service Account json file, please follow the official [instruction](https://firebase.google.com/docs/admin/setup).

    Put the file at project root.

    > :warning: Always make sure the JSON file is git-ignored!

4. Copy `.env.example` file and rename it to `.env` at project root.

    Change the dummy FIREBASE_DATABASE_URL value with your Firebase project databaseURL, you can find it on your Firebase Console 

5. Then start the server
    ```sh
    nodemon npm start
    ```

    OPTIONAL you may use yarn to resolve the packages other than npm

    ```sh
    (sudo)npm install -g yarn
    yarn install
    sudo nodemon yarn start
    ```

6. It should log successfully, and you can start using Firebase Admin SDK
7. For further reading, please visit [Express Firebase Middleware repo](https://github.com/antonybudianto/express-firebase-middleware)
8. In case of any furthur queries or suggestions, please use our channel to talk to us
[ in our messenger channel](https://join.slack.com/t/adysenlab/shared_invite/enQtNDIwMjkwNDU4NjQ3LTM0ZmQwYmNmNDBlNWJjZTVjOGU0Y2RhYTM2ZjBhNmYzZDEwMjFhMmY5ZDIzYWQ3NjEyYzNkZGI3YWViMzY1NjY)

9. Bring something to our notice (mail)

q8w0s0n6z9e8e8p0@adysenlab.slack.com


10. for publications and more products 
https://adysenlab.github.io/

## License
MIT

Copyright (c) 2016 Aloy A Sen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.