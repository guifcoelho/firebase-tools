# Use Firebase CLI with Docker

1. Add the `firebase` executable file in this repository to your `/usr/local/bin` folder.
2. Run `sudo chmod +x /usr/local/bin/firebase`.
3. On your command line, run `firebase`. It will pull the docker image and install firebase-tools.
4. Run `firebase login:ci`, open the provided link in the browser and login to Firebase, then copy the token.
5. Create a `.env` file in the same folder as your firebase environment.
6. Add the `FIREBASE_TOKEN` variable to the `.env` file and assign the generated token to it.
7. To serve with firebase-tools, run `firebase serve -o 0.0.0.0`
