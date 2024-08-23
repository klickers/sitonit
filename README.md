Clone this project to create an app to remind you of decisions you need to make. (After you sit on them, of course.)

## Running the project

Create an account on [Resend](https://resend.com) with an API key. Make sure to copy the `.env.example` file, fill out all variables, and rename it to `.env`.

Run the following command to start the project:

```
npm run dev
```

## A warning!

Resend currently only allows email scheduling up to 72 hours in advance. I have not yet added a provision for this in the code, so if the scheduling timeframe is set to, say, "5 days", the app frontend will seem to schedule the email as usual, though an error will be logged in the console. (The email will NOT be successfully scheduled.)
