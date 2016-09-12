# Title of your project
Describe your project :
* What does it do
* What problems it solves

## Motivation

What motivated you to create the project

## Installation

Provide steps of how to install the project

1. Download
2. Change some things
3. Test

## Tests

<b>How to get the registered users:</b>
<br/>
Action: GET<br/>
URI: /api/users<br/>
<br/>

<b>How to create a new event that is repeted every week:</b>
<br/>
Action: POST<br/>
URI: /api/users/{UserID}/events<br/>
BODY:<br/>
```javascript
{
  "UserID": 3,
  "Name": "Test post 2",
  "Location": "Via Skype",
  "Notes": "Some notes",
  "StartDate": "2016-09-12T17:00:00",
  "EndDate": "2016-09-12T18:00:00",
  "Recurrent": true,
  "EndBy": "2016-10-12T18:00:00",
  "FrequencyRule": 1,
  "Frequency": 1,
  "DayOfWeek": 3
}
```

<b>You may find more examples exporting this postman collection (<a href="https://www.getpostman.com/" target="_blank">Get postman</a>):</b>
<br/>
https://www.example.com

## Contributor

Juan Camilo Marin
