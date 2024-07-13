# NODEJS-FORM-SERVER

<img width="50%" height=auto src="./src/public/img/" />

## INTRODUCTION

Creating a Node.js server for sending forms by email.

## TECHNOLOGIES

- Node.js
- Express.js
- Bootstrap

## EXECUTION

1. Install the recommended version for most users of **Node.js** from the following link.

https://nodejs.org/en

2. Use the **npm** package manager to install.
3. Execute the command from the terminal located at ./NODEJS-FORM-SERVER.

```shell
npm i
```

4. Create a **Google** account through the following link.

https://support.google.com

5. Login with your account through the following link.

https://myaccount.google.com

6. Go to "Security", activate 2-step verification and perform the necessary verifications for your account.
7. Create an **App password** through the following link.

https://myaccount.google.com/apppasswords

8. Note: If Google indicates that this option is not enabled for your account after security checks, you may have to wait a few days.
9. To verify or delete your **App password** go to "Security" => "How you sign in to Google" => "2-Step Verification" => "App passwords".
10. Create an .env file inside ./NODEJS-FORM-SERVER and replace `googleaccountemail@gmail.com`, `App password` and `addressee@example.com` with the API credentials.

```js
EMAIL_USER = 'googleaccountemail@gmail.com'
EMAIL_PASS = 'App password'
EMAIL_TO = 'addressee@example.com'
PORT = 3000
```

## EXECUTION

11. Use the **npm** package manager to run.
12. Execute the command from the terminal located at ./NODEJS-FORM-SERVER.

```shell
npm run dev
```
