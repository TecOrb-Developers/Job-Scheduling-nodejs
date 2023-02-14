## Job Scheduling

## Introduction
    Job Scheduling in node js. Job Scheduling by using node-cron.

## Inside Cron * means -
┌────────────── second (0 - 59) (optional)
 │ ┌──────────── minute (0 - 59) 
 │ │ ┌────────── hour (0 - 23)
 │ │ │ ┌──────── day of the month (1 - 31)
 │ │ │ │ ┌────── month (1 - 12)
 │ │ │ │ │ ┌──── day of the week (0 - 6) (0 and 7 both represent Sunday)
 │ │ │ │ │ │
 │ │ │ │ │ │
 * * * * * *

## Setup Steps:
`npm install`
### local server
`npm run start:dev`
### prod build
`npm run build`
### prod build run
`node dist/index.js`


 