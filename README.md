## Build a push notifications server

The starting code for 
[Codelab: Build a push notifications server](http://web.dev/push-notifications-server-codelab/).

Uses Express.js, web-push.js, and lowdb.js

1. run 'npm install' to install dependencies.
2. In the terminal, run 'npx web-push generate-vapid-keys'. Copy the private key and public key values.
3. Open server.js and change the values of publicKey and privateKey.
4. Open public/index.js. Replace VAPID_PUBLIC_KEY with the value of your public key.
5. run 'node server.js'
