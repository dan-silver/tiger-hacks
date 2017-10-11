# Microsoft Graph @ Tiger Hacks
Guide to hacking with the Microsoft Graph at Tiger Hacks

## Getting Started 
Documentation - https://developer.microsoft.com/graph

Graph Explorer - https://developer.microsoft.com/graph/graph-explorer

## Curated API Queries

|                                                         |                                                                                           |
|---------------------------------------------------------|-------------------------------------------------------------------------------------------|
|Connect with students, teachers and alumni               |`GET https://graph.microsoft.com/v1.0/users?$filter=startsWith(displayName, 'Silver, Dan')`|
|Search your network by topic                             |`GET https://graph.microsoft.com/v1.0/me/people?$search="topic: hack"&$select=displayName` |
|Find my top connections among other students and faculty |`GET https://graph.microsoft.com/v1.0/me/people`                                           |
|Bring profile photos into your hack                      |`GET https://graph.microsoft.com/v1.0/users/das2c3@mail.missouri.edu/photo/$value`         |
|Send email from an @edu address                          |`POST https://graph.microsoft.com/v1.0/me/sendMail`                                        |
|Let students login to your app and get their profile info|`GET https://graph.microsoft.com/v1.0/me`                                                  |
|Schedule meeting time|`POST https://graph.microsoft.com/v1.0/me/findMeetingTimes`|
