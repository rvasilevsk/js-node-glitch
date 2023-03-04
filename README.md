[Deploying a Node.js app on Heroku within Minutes | by Kanchana Ranmuthu | Level Up Coding](https://levelup.gitconnected.com/deploying-a-node-js-app-on-heroku-within-minutes-9f50a3eff2fb)

```bash
node -V & npm -V

npm init -y
npm i express dotenv
npm i -D typescript @types/express @types/node
npx tsc --init
npm i -D concurrently nodemon

touch app.js

```
