# The SoapJack Project
YouTube classic soap opera videos in chronological order. The reponsitory contains the data of classic soap opera videos from YouTube in the approximate order of their broadcast dates.

This site is under construction and about 50% complete.

For questions, contact Bruce Hamilton at hamiltonbernique@icloud.com

To watcj a video from the data, copy the id from the json data into the YouTube search bar. Or you can construct the URL in in two ways:

- https://youtu.be/{id}
- https://www.youtube.com/watch?v={id}

The JSON data has the following elements:

| Field | Value |
| --- | --- |
| id | The YouTube id of the video. |
| parentid | Applies only to a series of videos constructed of parts, such as Part 1 of 3, 2 of 3, and so on. Uniquely indentifes those videos belonging to the series. |
| soap | Identifies the soap |
| category | A = Episode and episode content, B = Promos, opening, and closings |
| title | The title of the video. |
| date | The date, often just a year, the soap opera video was originally broadcast. Dates when only the year was known generally have the date of January 1 or June 1 of that yaer. Dates when only the month was known have the date as the first.|
| part | The part number of a series. |
| total | The total number of parts. |
| channel | The YouTube channel that hosts the video. The HamiltonBernique Project is very appreciateive of the fine work these soap fans have made, for without them this history making would not be possible.|
