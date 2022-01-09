---
layout: page
title: Configuration
permalink: /config/
---

Assessment Configuration
========================

```json
{
    "challenge_num": 5235, 
    "deadline": "2022-01-12T12:15:00-08:00",
    "x_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ0eXBlIjoidG9rZW4iLCJ1c2VyX2lkIjo2NTIxNiwic2Vzc2lvbl9pZCI6MjA1NTE4NjcsInJlZ2lvbiI6IiIsImlhdCI6MTY0MTYxMTE2OSwiZXhwIjoxNjQyODIwNzY5fQ.2otLzg9M6V5hQoTjQS0VA_wXJfWiXF9sqyGSACbscBg",
    "submissions_path": "resources/subs",
    "whitelist": ["test","test2"],
    "uid_csv_path": "resources/lookupSandbox.csv",
    "annotation_csv_path": "resources/annotationbank.csv"
}
```

A configuration file is required to run the code quality checker. It is a JSON file with the following keys: 
* "challenge_num": The challenge id
* "deadline": The deadline for the challenge in the format of "YYYY-MM-DDTHH:MM:SS-HH:MM"
* "x_token": The x-token for the bot account
* "submissions_path": The path to the student submissions folder
* "whitelist": A list of TA sections to filter
* "uid_csv_path": The path to the lookup table
* "annotation_csv_path": The path to the annotation bank