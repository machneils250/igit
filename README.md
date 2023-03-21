# iGit - Immediately Git a comment

Are you a lazy programmer that just puts "bug fix" in your git commits?
Then this app is for YOU!

iGit is an AI-powered app generates that easily generates a commit message just for you!

## Current Version: 0.001

In this version, you must input a result from your git diff (ex: git diff HEAD).
One file diff is already okay.
Once you submit, the app will create a message for you to easily copy-paste to your commits!

NOTE:
Since this is version 0.001, the accuracy of the commit message may not be accurate.
..But do you really care about accuracy if you used to put "bug fix" in your commits? LOL

## Setup

1. If you don’t have Node.js installed, [install it from here](https://nodejs.org/en/) (Node.js version >= 14.6.0 required)

2. Clone this repository

3. Navigate into the project directory

4. Install the requirements

   ```bash
   $ npm install
   ```

5. Make a copy of the example environment variables file

   On Linux systems: 
   ```bash
   $ cp .env.example .env
   ```
   On Windows:
   ```powershell
   $ copy .env.example .env
   ```
6. Add your [API key](https://platform.openai.com/account/api-keys) to the newly created `.env` file

7. Run the app

   ```bash
   $ npm run start:dev
   ```

You should now be able to access iGit at [http://localhost:3000](http://localhost:3000)!