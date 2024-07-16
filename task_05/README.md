# Task 5: Guess the user

## Rules
- You can use any external libraries
- Program must run without error
- Program should run in linux
- Only python code is acceptable

## Problem

### Definition
There are the following files JSON (JSON row in newline) in the datasets folder:
 - [mangas.json](./datasets/mangas.json)
 - [chapters.json](./datasets/chapters.json)
 - [search_histories.json](./datasets/search_histories.json) 
 - [user_mangas.json](./datasets/user_mangas.json)

Your task is to analyse the data provided in the files and estimate the following for each user:
- Favourite mangas for user
- Genres user is interested in
- Genres user could be interested in
- Average Active Time for week


### Input
You will be given a `user_id`

### Output
In output, you have to guesstimate the following:
- All the favourite mangas user likes
- Genres the user is interested in
- Genres the user could be interested in (different from point 2)
- Average Active Time during a week e.g., 
    MON: 14:00-15:00, 20:00-21:00
    TUE: NONE
    WED: 09:00-10:00
    THU: NONE
    FRI: 22:00-23:59
    SAT: 00:00-04:00, 18:00-21:00, 23:30-23:59
    SUN: 00:00-06:00, 22:00-23:59

## Submission
To submit your version of code follow the steps:

- Fork this repo
- In the `task_05` directory create your program file
- Add instructions, if any to run the file
- Last date of submission is: 19-07-2024 20:00


## Points
Points will be awarded based on how accurate the approximation is. For the closest guestimate, total **1500** points will be awared to the participant.