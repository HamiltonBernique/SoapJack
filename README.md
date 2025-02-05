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
| ![AMC](/z-media/AMC.png)<br>[All My Children](/AMC) (AMC) | Jan 1970 to Jan 2017<br>Total: 5333<br>Avg dur: 00:18:50<br>Total A: 5073 (95%)<br>Total B: 258 (5%) |
| ![ATWT](/z-media/ATWT.png)<br>[As The World Turns](/ATWT) (ATWT) | Apr 1957 to Sep 2010<br>Total: 644<br>Avg dur: 01:07:17<br>Total A: 573 (89%)<br>Total B: 71 (11%) |
| ![AW](/z-media/AW.png)<br>[Another World](/AW) (AW) | May 1964 to Jul 2002<br>Total: 3888<br>Avg dur: 09:37:34<br>Total A: 3808 (98%)<br>Total B: 80 (2%) |
| ![BB](/z-media/BB.png)<br>[Bold And The Beautiful](/BB) (BB) | Jan 1989 to Sep 2010<br>Total: 56<br>Avg dur: 00:05:32<br>Total A: 17 (30%)<br>Total B: 39 (70%) |
| ![BDAY](/z-media/BDAY.png)<br>[The Brighter Day](/BDAY) (BDAY) | Jan 1955 to Jan 1960<br>Total: 4<br>Avg dur: 00:14:29<br>Total A: 4 (100%)<br>Total B: 0 (0%) |
| ![CITY](/z-media/CITY.png)<br>[The City](/CITY) (CITY) | Jan 1991 to Feb 1997<br>Total: 28<br>Avg dur: 00:20:25<br>Total A: 27 (96%)<br>Total B: 1 (4%) |
| ![CPTL](/z-media/CPTL.png)<br>[Capitol](/CPTL) (CPTL) | Jan 1982 to Mar 1987<br>Total: 124<br>Avg dur: 00:20:06<br>Total A: 121 (98%)<br>Total B: 3 (2%) |
| ![DAYS](/z-media/DAYS.png)<br>[Days Of Our Lives](/DAYS) (DAYS) | Nov 1965 to Sep 2009<br>Total: 71<br>Avg dur: 00:04:34<br>Total A: 26 (37%)<br>Total B: 45 (63%) |
| ![DCTR](/z-media/DCTR.png)<br>[The Doctors](/DCTR) (DCTR) | Dec 1967 to Jan 1982<br>Total: 21<br>Avg dur: 00:04:57<br>Total A: 15 (71%)<br>Total B: 6 (29%) |
| ![EDGE](/z-media/EDGE.png)<br>[The Edge Of Night](/EDGE) (EDGE) | Jan 1955 to Dec 1984<br>Total: 504<br>Avg dur: 00:18:28<br>Total A: 485 (96%)<br>Total B: 19 (4%) |
| ![EGG](/z-media/EGG.png)<br>[The Egg and I](/EGG) (EGG) | Jan 1951 to Mar 1952<br>Total: 2<br>Avg dur: 00:13:41<br>Total A: 2 (100%)<br>Total B: 0 (0%) |
| ![EW10](/z-media/EW10.png)<br>[Emergency Ward 10](/EW10) (EW10) | Aug 1958 to Aug 1959<br>Total: 3<br>Avg dur: 00:20:14<br>Total A: 3 (100%)<br>Total B: 0 (0%) |
| ![EMMY](/z-media/EMMY.png)<br>[Daytime Emmy Awards](/EMMY) (EMMY) | Jun 1980 to Jun 2012<br>Total: 119<br>Avg dur: 00:18:15<br>Total A: 116 (97%)<br>Total B: 2 (2%) |
| ![FHY](/z-media/FHY.png)<br>[The First Hundred Years](/FHY) (FHY) | Jan 1952 to Jan 1952<br>Total: 2<br>Avg dur: 00:14:25<br>Total A: 2 (100%)<br>Total B: 0 (0%) |
| ![GH](/z-media/GH.png)<br>[General Hospital](/GH) (GH) | Jan 1962 to Oct 2016<br>Total: 7770<br>Avg dur: 00:08:40<br>Total A: 7493 (96%)<br>Total B: 275 (4%) |
| ![GENR](/z-media/GENR.png)<br>[Generations](/GENR) (GENR) | Jan 1989 to Jan 1991<br>Total: 28<br>Avg dur: 00:14:30<br>Total A: 28 (100%)<br>Total B: 0 (0%) |
| ![GL](/z-media/GL.png)<br>[Guiding Light](/GL) (GL) | Jul 1952 to Sep 2009<br>Total: 972<br>Avg dur: 00:57:59<br>Total A: 892 (92%)<br>Total B: 79 (8%) |
| ![HFLS](/z-media/HFLS.png)<br>[Hawkins Falls](/HFLS) (HFLS) | Oct 1950 to Apr 1955<br>Total: 7<br>Avg dur: 00:13:22<br>Total A: 7 (100%)<br>Total B: 0 (0%) |
| ![LL](/z-media/LL.png)<br>[Love of Life](/LL) (LL) | Jan 1953 to Oct 1982<br>Total: 27<br>Avg dur: 00:15:22<br>Total A: 26 (96%)<br>Total B: 1 (4%) |
| ![LMST](/z-media/LMST.png)<br>[Love is a Many Slendored Thing](/LMST) (LMST) | Dec 1967 to Mar 1973<br>Total: 5<br>Avg dur: 05:56:18<br>Total A: 5 (100%)<br>Total B: 0 (0%) |
| ![LVNG](/z-media/LVNG.png)<br>[Loving](/LVNG) (LVNG) | Jan 1983 to May 2009<br>Total: 102<br>Avg dur: 00:12:03<br>Total A: 85 (83%)<br>Total B: 17 (17%) |
| ![MSTR](/z-media/MSTR.png)<br>[Morning Star](/MSTR) (MSTR) | Mar 1966 to Jun 1966<br>Total: 5<br>Avg dur: 00:21:15<br>Total A: 5 (100%)<br>Total B: 0 (0%) |
| ![OLTL](/z-media/OLTL.png)<br>[One Life To Live](/OLTL) (OLTL) | Jan 1968 to Jan 2017<br>Total: 2748<br>Avg dur: 01:08:14<br>Total A: 2369 (86%)<br>Total B: 369 (13%) |
| ![PP](/z-media/PP.png)<br>[Peyton Place](/PP) (PP) | Sep 1964 to Jun 1969<br>Total: 957<br>Avg dur: 00:13:14<br>Total A: 956 (100%)<br>Total B: 1 (0%) |
| ![PC](/z-media/PC.png)<br>[Port Charles](/PC) (PC) | Jan 1997 to Oct 2003<br>Total: 1627<br>Avg dur: 00:20:54<br>Total A: 1622 (100%)<br>Total B: 3 (0%) |
| ![RARE](/z-media/RARE.png)<br>[Rare Treasures](/RARE) (RARE) | Sep 1953 to Jun 1971<br>Total: 9<br>Avg dur: 00:15:33<br>Total A: 9 (100%)<br>Total B: 0 (0%) |
| ![RH](/z-media/RH.png)<br>[Ryan's Hope](/RH) (RH) | Jan 1975 to Oct 1989<br>Total: 210<br>Avg dur: 00:22:04<br>Total A: 135 (64%)<br>Total B: 75 (36%) |
| ![SB](/z-media/SB.png)<br>[Santa Barbara](/SB) (SB) | Jun 1984 to Jan 1992<br>Total: 317<br>Avg dur: 00:13:27<br>Total A: 312 (98%)<br>Total B: 5 (2%) |
| ![SFT](/z-media/SFT.png)<br>[Search For Tomorrow](/SFT) (SFT) | Sep 1951 to Dec 1986<br>Total: 245<br>Avg dur: 00:37:21<br>Total A: 223 (91%)<br>Total B: 21 (9%) |
| ![SS](/z-media/SS.png)<br>[Secret Storm](/SS) (SS) | Jan 1955 to Apr 1973<br>Total: 19<br>Avg dur: 00:13:52<br>Total A: 16 (84%)<br>Total B: 3 (16%) |
| ![SSB](/z-media/SSB.png)<br>[Sunset Beach](/SSB) (SSB) | Jan 1997 to Dec 1998<br>Total: 30<br>Avg dur: 00:00:31<br>Total A: 6 (20%)<br>Total B: 24 (80%) |
| ![SSET](/z-media/SSET.png)<br>[Summerset](/SSET) (SSET) | Nov 1972 to Jan 1973<br>Total: 2<br>Avg dur: 00:15:19<br>Total A: 1 (50%)<br>Total B: 1 (50%) |
| ![TX](/z-media/TX.png)<br>[Texas](/TX) (TX) | Jan 1980 to Jan 1992<br>Total: 471<br>Avg dur: 00:50:38<br>Total A: 416 (88%)<br>Total B: 55 (12%) |
| ![VALL](/z-media/VALL.png)<br>[Valient Lady](/VALL) (VALL) | Nov 1953 to Jan 1955<br>Total: 5<br>Avg dur: 00:12:52<br>Total A: 5 (100%)<br>Total B: 0 (0%) |
| ![YR](/z-media/YR.png)<br>[Young And The Restless](/YR) (YR) | Jan 1973 to Jan 2016<br>Total: 54<br>Avg dur: 00:01:09<br>Total A: 19 (35%)<br>Total B: 35 (65%) |

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

| Import a CSV file |
| --- |
| ![Import CSV file](/-media/z-csvfile.png)


## Contributions and corrections

Soap fans are encouraged to email feedback and corrections, or share an online spreadsheet from a CSV file, to `hamiltonbernique@icloud.com`.

If you have well formed JSON data to contribute, you're welcome to fork the repository and submit a pull request.



