# The SoapJack Project

The SoapJack Project is to create a catalog of YouTube classic soap opera videos organized by their original air dates as much as possible. Data is provided in JSON and CSV formats. For questions and feedback, email Bruce Hamilton at `hamiltonbernique@icloud.com`

The data has the following properties:

| Property | Description |
| --- | --- |
| id | The YouTube id of the video. |
| parentid | Identifies the videos that a part of a series, such as Part 1 of 3, 2 of 3, and so on. These videos have the  same date as well as the same parentid. |
| soap | The code that identifies the soap opera. See their full names below. |
| category | A = Episode and episode content, B = Promos, opening, and closings. |
| title | The title of the video. For the most part, original titling by the channel owner is preserved but edited for length and consistency. Titles that just had the date and name of the soap are retitled as 'Episode'. |
| date | The date, often just a year, the episode was originally broadcast. Dates when only the year is known have the date as January 1 or June 1. Dates when only the month is known use the first of the month. |
| part | The part number of a series. |
| total | The total number of parts. |
| channel | The YouTube channel that hosts the video. The HamiltonBernique Project is very appreciative of the fine work these soap fans have made, for without them this history making would not be possible.|

See [How to watch videos](#how-to-watch-videos).

## Soap Operas

Categories:
A = Episodes and clips

B = Promos, open/closings

| Soap Opera | Stats
| --- | --- |
| ![AMC](/z-media/AMC.png)<br>[All My Children](/AMC) (AMC) | January 1970 to January 2017<br>Total: 5333<br>Avg dur: 00:18:50<br>Total A: 5073 (95%)<br>Total B: 258 (5%) |
| ![ATWT](/z-media/ATWT.png)<br>[As The World Turns](/ATWT) (ATWT) | April 1957 to September 2010<br>Total: 644<br>Avg dur: 01:07:17<br>Total A: 573 (89%)<br>Total B: 71 (11%) |
| ![AW](/z-media/AW.png)<br>[Another World](/AW) (AW) | May 1964 to July 2002<br>Total: 3888<br>Avg dur: 09:37:34<br>Total A: 3808 (98%)<br>Total B: 80 (2%) |
| ![BB](/z-media/BB.png)<br>[Bold And The Beautiful](/BB) (BB) | January 1989 to September 2010<br>Total: 56<br>Avg dur: 00:05:32<br>Total A: 17 (30%)<br>Total B: 39 (70%) |
| ![BDAY](/z-media/BDAY.png)<br>[The Brighter Day](/BDAY) (BDAY) | January 1955 to January 1960<br>Total: 4<br>Avg dur: 00:14:29<br>Total A: 4 (100%)<br>Total B: 0 (0%) |
| ![CITY](/z-media/CITY.png)<br>[The City](/CITY) (CITY) | January 1991 to February 1997<br>Total: 28<br>Avg dur: 00:20:25<br>Total A: 27 (96%)<br>Total B: 1 (4%) |
| ![CPTL](/z-media/CPTL.png)<br>[Capitol](/CPTL) (CPTL) | January 1982 to March 1987<br>Total: 124<br>Avg dur: 00:20:06<br>Total A: 121 (98%)<br>Total B: 3 (2%) |
| ![DAYS](/z-media/DAYS.png)<br>[Days Of Our Lives](/DAYS) (DAYS) | November 1965 to September 2009<br>Total: 71<br>Avg dur: 00:04:34<br>Total A: 26 (37%)<br>Total B: 45 (63%) |
| ![DCTR](/z-media/DCTR.png)<br>[The Doctors](/DCTR) (DCTR) | December 1967 to January 1982<br>Total: 21<br>Avg dur: 00:04:57<br>Total A: 15 (71%)<br>Total B: 6 (29%) |
| ![EDGE](/z-media/EDGE.png)<br>[The Edge Of Night](/EDGE) (EDGE) | January 1955 to December 1984<br>Total: 504<br>Avg dur: 00:18:28<br>Total A: 485 (96%)<br>Total B: 19 (4%) |
| ![EGG](/z-media/EGG.png)<br>[The Egg and I](/EGG) (EGG) | January 1951 to March 1952<br>Total: 2<br>Avg dur: 00:13:41<br>Total A: 2 (100%)<br>Total B: 0 (0%) |
| ![EW10](/z-media/EW10.png)<br>[Emergency Ward 10](/EW10) (EW10) | August 1958 to August 1959<br>Total: 3<br>Avg dur: 00:20:14<br>Total A: 3 (100%)<br>Total B: 0 (0%) |
| ![EMMY](/z-media/EMMY.png)<br>[Daytime Emmy Awards](/EMMY) (EMMY) | June 1980 to June 2012<br>Total: 119<br>Avg dur: 00:18:15<br>Total A: 116 (97%)<br>Total B: 2 (2%) |
| ![FHY](/z-media/FHY.png)<br>[The First Hundred Years](/FHY) (FHY) | January 1952 to January 1952<br>Total: 2<br>Avg dur: 00:14:25<br>Total A: 2 (100%)<br>Total B: 0 (0%) |
| ![GH](/z-media/GH.png)<br>[General Hospital](/GH) (GH) | January 1962 to October 2016<br>Total: 7770<br>Avg dur: 00:08:40<br>Total A: 7493 (96%)<br>Total B: 275 (4%) |
| ![GENR](/z-media/GENR.png)<br>[Generations](/GENR) (GENR) | January 1989 to January 1991<br>Total: 28<br>Avg dur: 00:14:30<br>Total A: 28 (100%)<br>Total B: 0 (0%) |
| ![GL](/z-media/GL.png)<br>[Guiding Light](/GL) (GL) | July 1952 to September 2009<br>Total: 972<br>Avg dur: 00:57:59<br>Total A: 892 (92%)<br>Total B: 79 (8%) |
| ![HFLS](/z-media/HFLS.png)<br>[Hawkins Falls](/HFLS) (HFLS) | October 1950 to April 1955<br>Total: 7<br>Avg dur: 00:13:22<br>Total A: 7 (100%)<br>Total B: 0 (0%) |
| ![LL](/z-media/LL.png)<br>[Love of Life](/LL) (LL) | January 1953 to October 1982<br>Total: 27<br>Avg dur: 00:15:22<br>Total A: 26 (96%)<br>Total B: 1 (4%) |
| ![LMST](/z-media/LMST.png)<br>[Love is a Many Slendored Thing](/LMST) (LMST) | December 1967 to March 1973<br>Total: 5<br>Avg dur: 05:56:18<br>Total A: 5 (100%)<br>Total B: 0 (0%) |
| ![LVNG](/z-media/LVNG.png)<br>[Loving](/LVNG) (LVNG) | January 1983 to May 2009<br>Total: 102<br>Avg dur: 00:12:03<br>Total A: 85 (83%)<br>Total B: 17 (17%) |
| ![MSTR](/z-media/MSTR.png)<br>[Morning Star](/MSTR) (MSTR) | March 1966 to June 1966<br>Total: 5<br>Avg dur: 00:21:15<br>Total A: 5 (100%)<br>Total B: 0 (0%) |
| ![OLTL](/z-media/OLTL.png)<br>[One Life To Live](/OLTL) (OLTL) | January 1968 to January 2017<br>Total: 2748<br>Avg dur: 01:08:14<br>Total A: 2369 (86%)<br>Total B: 369 (13%) |
| ![PP](/z-media/PP.png)<br>[Peyton Place](/PP) (PP) | September 1964 to June 1969<br>Total: 957<br>Avg dur: 00:13:14<br>Total A: 956 (100%)<br>Total B: 1 (0%) |
| ![PC](/z-media/PC.png)<br>[Port Charles](/PC) (PC) | January 1997 to October 2003<br>Total: 1627<br>Avg dur: 00:20:54<br>Total A: 1622 (100%)<br>Total B: 3 (0%) |
| ![RARE](/z-media/RARE.png)<br>[Rare Treasures](/RARE) (RARE) | September 1953 to June 1971<br>Total: 9<br>Avg dur: 00:15:33<br>Total A: 9 (100%)<br>Total B: 0 (0%) |
| ![RH](/z-media/RH.png)<br>[Ryan's Hope](/RH) (RH) | January 1975 to October 1989<br>Total: 210<br>Avg dur: 00:22:04<br>Total A: 135 (64%)<br>Total B: 75 (36%) |
| ![SB](/z-media/SB.png)<br>[Santa Barbara](/SB) (SB) | June 1984 to January 1992<br>Total: 317<br>Avg dur: 00:13:27<br>Total A: 312 (98%)<br>Total B: 5 (2%) |
| ![SFT](/z-media/SFT.png)<br>[Search For Tomorrow](/SFT) (SFT) | September 1951 to December 1986<br>Total: 245<br>Avg dur: 00:37:21<br>Total A: 223 (91%)<br>Total B: 21 (9%) |
| ![SS](/z-media/SS.png)<br>[Secret Storm](/SS) (SS) | January 1955 to April 1973<br>Total: 19<br>Avg dur: 00:13:52<br>Total A: 16 (84%)<br>Total B: 3 (16%) |
| ![SSB](/z-media/SSB.png)<br>[Sunset Beach](/SSB) (SSB) | January 1997 to December 1998<br>Total: 30<br>Avg dur: 00:00:31<br>Total A: 6 (20%)<br>Total B: 24 (80%) |
| ![SSET](/z-media/SSET.png)<br>[Summerset](/SSET) (SSET) | November 1972 to January 1973<br>Total: 2<br>Avg dur: 00:15:19<br>Total A: 1 (50%)<br>Total B: 1 (50%) |
| ![TX](/z-media/TX.png)<br>[Texas](/TX) (TX) | January 1980 to January 1992<br>Total: 471<br>Avg dur: 00:50:38<br>Total A: 416 (88%)<br>Total B: 55 (12%) |
| ![VALL](/z-media/VALL.png)<br>[Valient Lady](/VALL) (VALL) | November 1953 to January 1955<br>Total: 5<br>Avg dur: 00:12:52<br>Total A: 5 (100%)<br>Total B: 0 (0%) |
| ![YR](/z-media/YR.png)<br>[Young And The Restless](/YR) (YR) | January 1973 to January 2016<br>Total: 54<br>Avg dur: 00:01:09<br>Total A: 19 (35%)<br>Total B: 35 (65%) |


## How to watch videos

You can watch video in three ways.

### Copy id into YouTube search bar

This method is the easiest. Copy the id from the JSON data into the YouTube search bar. Select the video from the search results. If not in the results, construct a YouTube URL.

| Select ID from JSON data |
| --- |
| ![Select ID from JSON data](/z-media/z-selectid.png) |


### Construct a YouTube URL

Copy the id from the JSON data and append to either of the following URLs, where `{id}` is the id placeholder.

- `https://youtu.be/{id}`
- `https://www.youtube.com/watch?v={id}`

### Use a CSV file

Download the CSV file and import it into a spreadsheet, as shown here using Google sheets.

1. Select the CSV file in the repository and select **Download raw file** in the upper-right corner to download to your computer.
1. In Google Sheets, select **Import** from the **File** menu and select the **Upload** tab to upload the CSV file from your computer. Set the import location to replace the current sheet or other desired option. Keep the `Convert text to numbers, dates, and formulas` option selected, as otherwise the YouTube link will not be operational.
1. Click the link in column A.

| Import a CSV file |
| --- |
| ![Import CSV file](/z-media/z-csvfile.png) |


## Contributions and corrections

Soap fans are encouraged to email feedback and corrections, or share an online spreadsheet from a CSV file, to `hamiltonbernique@icloud.com`.

If you have well formed JSON data to contribute, you're welcome to fork the repository and submit a pull request.



