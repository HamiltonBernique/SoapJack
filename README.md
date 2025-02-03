# The SoapJack Project

Presenting YouTube classic soap opera videos in chronological order. The repository contains the data of classic soap opera videos from YouTube in the approximate order of their broadcast dates.

This site is under construction and is roughly 50% complete.

For questions, contact Bruce Hamilton at `hamiltonbernique@icloud.com`

To watch a video from the data, copy the id from the json data into the YouTube search bar. Or you can construct the URL in in two ways:

- `https://youtu.be/{id}`
- `https://www.youtube.com/watch?v={id}`

The JSON data has the following elements:

| Field | Value |
| --- | --- |
| id | The YouTube id of the video. |
| parentid | Applies only to a series of videos constructed of parts, such as Part 1 of 3, 2 of 3, and so on. Uniquely identifies that are parts of a series. |
| soap | Identifies the soap |
| category | A = Episode and episode content, B = Promos, opening, and closings |
| title | The title of the video. |
| date | The date, often just a year, the soap opera video was originally broadcast. Dates when only the year was known generally have the date of January 1 or June 1 of that year. Dates when only the month was known have the date as the first.|
| part | The part number of a series. |
| total | The total number of parts. |
| channel | The YouTube channel that hosts the video. The HamiltonBernique Project is very appreciative of the fine work these soap fans have made, for without them this history making would not be possible.|

## Soap Operas

| Soap Opera | Stats
| --- | --- |
| ![AMC](/z-media/AMC.png)<br>All My Children (AMC) | 01/01/1970 to 01/01/2017<br>Total: 5340, avg duration: 00:18:49<br>Total A: 5081 (95.15%)<br>Total B: 257 (4.81%) |
| ![ATWT](/z-media/ATWT.png)<br>As The World Turns (ATWT) | 04/10/1957 to 09/17/2010<br>Total: 644, avg duration: 01:07:17<br>Total A: 573 (88.98%)<br>Total B: 71 (11.02%) |
| ![AW](/z-media/AW.png)<br>Another World (AW) | 5/22/1964 to 7/15/2002<br>Total: 3888, avg duration: 09:37:34<br>Total A: 3808 (97.94%)<br>Total B: 80 (2.06%) |
| ![BB](/z-media/BB.png)<br>Bold And The Beautiful (BB) | 01/01/1989 to 09/22/2010<br>Total: 56, avg duration: 00:05:32<br>Total A: 17 (30.36%)<br>Total B: 39 (69.64%) |
| ![CITY](/z-media/CITY.png)<br>The City (CITY) | 01/01/1991 to 2/6/1997<br>Total: 28, avg duration: 00:20:25<br>Total A: 27 (96.43%)<br>Total B: 1 (3.57%) |
| ![CPTL](/z-media/CPTL.png)<br>Capitol (CPTL) | 01/01/1982 to 3/13/1987<br>Total: 124, avg duration: 00:20:06<br>Total A: 121 (97.58%)<br>Total B: 3 (2.42%) |
| ![DAYS](/z-media/DAYS.png)<br>Days Of Our Lives (DAYS) | 11/08/1965 to 9/1/2009<br>Total: 68, avg duration: 00:02:53<br>Total A: 23 (33.82%)<br>Total B: 45 (66.18%) |
| ![DCTR](/z-media/DCTR.png)<br>The Doctors (DCTR) | 12/01/1967 to 01/01/1982<br>Total: 21, avg duration: 00:04:57<br>Total A: 15 (71.43%)<br>Total B: 6 (28.57%) |
| ![EDGE](/z-media/EDGE.png)<br>Edge Of Night (EDGE) | 01/01/1955 to 12/28/1984<br>Total: 504, avg duration: 00:18:28<br>Total A: 485 (96.23%)<br>Total B: 19 (3.77%) |
| ![EMMY](/z-media/EMMY.png)<br>Daytime Emmy Awards (EMMY) | 06/04/1980 to 06/17/2012<br>Total: 119, avg duration: 00:18:15<br>Total A: 116 (97.48%)<br>Total B: 2 (1.68%) |
| ![GH](/z-media/GH.png)<br>General Hospital (GH) | 01/01/1962 to 10/18/2016<br>Total: 7770, avg duration: 00:08:40<br>Total A: 7493 (96.44%)<br>Total B: 275 (3.54%) |
| ![GENR](/z-media/GENR.png)<br>Generations (GENR) | 01/01/1989 to 01/01/1991<br>Total: 28, avg duration: 00:14:30<br>Total A: 28 (100.00%)<br>Total B: 0 (0.00%) |
| ![GL](/z-media/GL.png)<br>Guiding Light (GL) | 07/10/1952 to 09/18/2009<br>Total: 972, avg duration: 00:57:59<br>Total A: 892 (91.77%)<br>Total B: 79 (8.13%) |
| ![LL](/z-media/LL.png)<br>Love of Life (LL) | 01/01/1953 to 10/15/1982<br>Total: 26, avg duration: 00:15:25<br>Total A: 25 (96.15%)<br>Total B: 1 (3.85%) |
| ![LMST](/z-media/LMST.png)<br>Love is a Many Slendored Thing (LMST) | 12/01/1967 to 03/01/1973<br>Total: 4, avg duration: 07:18:14<br>Total A: 4 (100.00%)<br>Total B: 0 (0.00%) |
| ![LVNG](/z-media/LVNG.png)<br>Loving (LVNG) | 01/01/1983 to 05/10/2009<br>Total: 102, avg duration: 00:12:03<br>Total A: 85 (83.33%)<br>Total B: 17 (16.67%) |
| ![OLTL](/z-media/OLTL.png)<br>One Life To Live (OLTL) | 01/01/1968 to 01/01/2017<br>Total: 2748, avg duration: 01:08:14<br>Total A: 2369 (86.21%)<br>Total B: 369 (13.43%) |
| ![PP](/z-media/PP.png)<br>Peyton Place (PP) | 09/15/1964 to 6/2/1969<br>Total: 959, avg duration: 00:13:16<br>Total A: 958 (99.90%)<br>Total B: 1 (0.10%) |
| ![PC](/z-media/PC.png)<br>Port Charles (PC) | 01/01/1997 to 10/03/2003<br>Total: 1627, avg duration: 00:20:54<br>Total A: 1622 (99.69%)<br>Total B: 3 (0.18%) |
| ![RH](/z-media/RH.png)<br>Ryan's Hope (RH) | 01/01/1975 to 10/01/1989<br>Total: 210, avg duration: 00:22:04<br>Total A: 135 (64.29%)<br>Total B: 75 (35.71%) |
| ![SB](/z-media/SB.png)<br>Santa Barbara (SB) | 6/1/1984 to 01/01/1992<br>Total: 317, avg duration: 00:13:27<br>Total A: 312 (98.42%)<br>Total B: 5 (1.58%) |
| ![SFT](/z-media/SFT.png)<br>Search For Tomorrow (SFT) | 09/03/1951 to 12/24/1986<br>Total: 245, avg duration: 00:37:21<br>Total A: 223 (91.02%)<br>Total B: 21 (8.57%) |
| ![SS](/z-media/SS.png)<br>Secret Storm (SS) | 01/01/1955 to 04/26/1973<br>Total: 19, avg duration: 00:13:52<br>Total A: 16 (84.21%)<br>Total B: 3 (15.79%) |
| ![SSB](/z-media/SSB.png)<br>Sunset Beach (SSB) | 01/01/1997 to 12/25/1998<br>Total: 30, avg duration: 00:00:31<br>Total A: 6 (20.00%)<br>Total B: 24 (80.00%) |
| ![SSET](/z-media/SSET.png)<br>Summerset (SSET) | 11/07/1972 to 01/01/1973<br>Total: 2, avg duration: 00:15:19<br>Total A: 1 (50.00%)<br>Total B: 1 (50.00%) |
| ![TX](/z-media/TX.png)<br>Texas (TX) | 01/01/1980 to 12/31/1982<br>Total: 101, avg duration: 00:12:40<br>Total A: 71 (70.30%)<br>Total B: 30 (29.70%) |
| ![YR](/z-media/YR.png)<br>Young And The Restless (YR) | 01/01/1973 to 01/01/2016<br>Total: 54, avg duration: 00:01:09<br>Total A: 19 (35.19%)<br>Total B: 35 (64.81%) |



