# Microsoft Graph @ Tiger Hacks
Guide to hacking with the Microsoft Graph at Tiger Hacks

## Getting Started
* Quick starts for Android, iOS, Node, PHP, etc. - https://developer.microsoft.com/graph/quick-start
* Graph Explorer - https://developer.microsoft.com/graph/graph-explorer
* Documentation - https://developer.microsoft.com/graph

## Curated API Queries

|                                                         |                                                                                           |
|---------------------------------------------------------|-------------------------------------------------------------------------------------------|
|Connect with students, teachers and alumni               |[`GET https://graph.microsoft.com/v1.0/users?$filter=startsWith(displayName, 'Silver, Dan')`][user-search]|
|Search your network by topic                             |[`GET https://graph.microsoft.com/v1.0/me/people?$search="topic: homework"&$select=displayName`][topic-search]|
|Find my top connections among other students and faculty |[`GET https://graph.microsoft.com/v1.0/me/people`][me-people]                                           |
|Bring profile photos into your hack                      |[`GET https://graph.microsoft.com/v1.0/users/das2c3@mail.missouri.edu/photo/$value`][profile-photo]         |
|Send email from an @edu address                          |`POST https://graph.microsoft.com/v1.0/me/sendMail`                                        |
|Let students login to your app and get their profile info|[`GET https://graph.microsoft.com/v1.0/me`][me]                                                  |
|Schedule meeting time|`POST https://graph.microsoft.com/v1.0/me/findMeetingTimes`|



[topic-search]: https://developer.microsoft.com/en-us/graph/graph-explorer?request=me/people?$search=%22topic:%20homework%22&$select=displayName&method=GET&version=v1.0

[user-search]: https://developer.microsoft.com/en-us/graph/graph-explorer?request=users?$filter=startsWith(displayName,%20'Silver,%20Dan')&method=GET&version=v1.0&GraphUrl=https://graph.microsoft.com


[me-people]: https://developer.microsoft.com/en-us/graph/graph-explorer?request=me/people&method=GET&version=v1.0&GraphUrl=https://graph.microsoft.com

[profile-photo]: https://developer.microsoft.com/en-us/graph/graph-explorer?request=users/das2c3@mail.missouri.edu/photo/$value&method=GET&version=v1.0&GraphUrl=https://graph.microsoft.com

[me]: https://developer.microsoft.com/en-us/graph/graph-explorer?request=me&method=GET&version=v1.0&GraphUrl=https://graph.microsoft.com
