# SoapJack
Data of classic soap opera videos from YouTube in the approximate order of their broadcast dates.

The JSON data has the following elements:

| Field | Value |
| --- | --- |
| id | The YouTube id of the video. To consruct the URL:<br>https://youtu.be/{id} or:<br>https://www.youtube.com/watch?v={id} |
| parentid | Applies only to a series of videos used to construct a larger presentation. Part 1 of 3, 2 of 3, and so on. Uniquely indentifes those videos belonging to the series - useful for UI in an app. |
| soap | Identifies the soap |
| category | A = Episode and episode content, B = Promos, opening, and closings |
| title | The title of the video. |
| date | The date (approx) the soap opera video was originally broadcast. |
| part | The part number of a series. |
| total | The total number of parts. |
| channel | The YouTube channel that hosts the video. |
