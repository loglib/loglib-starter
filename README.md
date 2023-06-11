# LOGLIB Starter

## Description

a quick loglib starter that you can deploy.

## Usage

1. clone this repo and run `pnpm i` to install dependencies.
2. change .env.example to .env and fill in the required env variables
3. migrate your database with `pnpm prisma migrate` or `pnpm prisma db push`
4. You can now deploy but if you're deploying to platforms other than vercel you need to setup location resolver for your server. [Read more](https://github.com/loglib/loglib/#resolving-user-location-from-ip)
5. Now go to your project where you want to track and put loglib url in the `LOGLIB_URL` or `NEXT_PUBLIC_LOGLIB_URL` env variable.
6. Install the loglib tracker in `pnpm i @loglib/tracker`
7. Follow the instructions in the [doc](https://github.com/LogLib/loglib#loglib-tracker) to setup the tracker.
