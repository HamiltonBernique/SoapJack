# The SoapJack Project

The SoapJack Project is to create a catalog of YouTube classic soap opera video links organized by their original air dates -- as much as possible. Data is provided in JSON and CSV formats. For questions and feedback, email Bruce Hamilton at `hamiltonbernique@icloud.com`. 

There are currently over 26,000 links in the repository. The repository is organized alphabetically by the soap opera codes (listed with their names in the next section) with JSON and CSV files in each. For large datasets, the files are organized by decade.

Such a dataset is indeed malleable and loosely defined. The aim is an inventory of those classic soap operas that aired from the 1950s to the 2010s, essentially to capture content where there are no means to view it except by the efforts of the devoted fans who uploaded their treasures to YouTube. Some soaps are available in their entirety such as Dark Shadows, so that soap is not included. The data has the following criteria, but your input in more than welcome:

- Any episode or partial episode, including clips of scenes and clips of storylines over time.
- Episode opening sequences and closing credits.
- Soap promos.
- Daytime Emmy Award content. This is only exception to episode content.

The following content is not included:

- Tributes (except by the soap or network itself).
- Montages.
- Reimagined or altered content.
- Appearances by soap stars in talk shows, movies, and other venues.

The data has the following properties:

| Property | Description |
| --- | --- |
| id | The YouTube ID of the video. |
| parentid | Identifies videos that a part of a series, such as Part 1 of 3, 2 of 3, and so on. These videos have the  same date as well as the same parentid. This value generated for SoapJack data, and does not exist in YouTube. |
| soap | The code that identifies the soap opera. See their full names below. |
| category | A = Episodes and episode clips, B = Promos, opening, and closings. |
| title | The title of the video. For the most part, original titling by the channel owner is preserved but edited for length and consistency. Titles that just had the date and name of the soap are retitled as 'Episode'. |
| date | The date, often just a year, the episode was originally broadcast. Dates when only the year is known have the date as January 1 or June 1. Dates when only the month is known use the first of the month. |
| part | The part number of a series. |
| total | The total number of parts in the series. |
| channel | The YouTube channel that hosts the video. The HamiltonBernique Project is very appreciative of the fine work these soap fans have made, for without them this history making would not be possible. Visit the [HamiltonBernique](https://www.youtube.com/@HamiltonBernique) YouTube channel for All My Children and One Life to Live videos. |

See [How to watch videos](#how-to-watch-videos).

## Soap Operas

Categories:
A = Episodes and clips

B = Promos, open/closings

| Soap Opera | Stats
| --- | --- |
| ![AMC](/z-media/AMC.png)<br>[All My Children](/AMC) (AMC) | January 1970 to January 2017<br>Total: 5333<br>Avg dur: 00:18:50<br>A: 5073 (95%)<br>B: 258 (5%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/AMC") |
| ![ATWT](/z-media/ATWT.png)<br>[As The World Turns](/ATWT) (ATWT) | April 1957 to September 2010<br>Total: 644<br>Avg dur: 01:07:17<br>A: 573 (89%)<br>B: 71 (11%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/ATWT") |
| ![AW](/z-media/AW.png)<br>[Another World](/AW) (AW) | May 1964 to July 2002<br>Total: 3888<br>Avg dur: 09:37:34<br>A: 3808 (98%)<br>B: 80 (2%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/AW") |
| ![BB](/z-media/BB.png)<br>[Bold And The Beautiful](/BB) (BB) | January 1989 to September 2010<br>Total: 56<br>Avg dur: 00:05:32<br>A: 17 (30%)<br>B: 39 (70%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/BB") |
| ![BDAY](/z-media/BDAY.png)<br>[The Brighter Day](/BDAY) (BDAY) | January 1955 to January 1960<br>Total: 4<br>Avg dur: 00:14:29<br>A: 4 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/BDAY") |
| ![CITY](/z-media/CITY.png)<br>[The City](/CITY) (CITY) | January 1991 to February 1997<br>Total: 28<br>Avg dur: 00:20:25<br>A: 27 (96%)<br>B: 1 (4%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/CITY") |
| ![CPTL](/z-media/CPTL.png)<br>[Capitol](/CPTL) (CPTL) | January 1982 to March 1987<br>Total: 124<br>Avg dur: 00:20:06<br>A: 121 (98%)<br>B: 3 (2%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/CPTL") |
| ![DAYS](/z-media/DAYS.png)<br>[Days Of Our Lives](/DAYS) (DAYS) | November 1965 to September 2009<br>Total: 71<br>Avg dur: 00:04:34<br>A: 26 (37%)<br>B: 45 (63%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/DAYS") |
| ![DCTR](/z-media/DCTR.png)<br>[The Doctors](/DCTR) (DCTR) | December 1967 to January 1982<br>Total: 21<br>Avg dur: 00:04:57<br>A: 15 (71%)<br>B: 6 (29%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/DCTR") |
| ![EDGE](/z-media/EDGE.png)<br>[The Edge Of Night](/EDGE) (EDGE) | January 1955 to December 1984<br>Total: 504<br>Avg dur: 00:18:28<br>A: 485 (96%)<br>B: 19 (4%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/EDGE") |
| ![EGG](/z-media/EGG.png)<br>[The Egg and I](/EGG) (EGG) | January 1951 to March 1952<br>Total: 2<br>Avg dur: 00:13:41<br>A: 2 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/EGG") |
| ![EW10](/z-media/EW10.png)<br>[Emergency Ward 10](/EW10) (EW10) | August 1958 to August 1959<br>Total: 3<br>Avg dur: 00:20:14<br>A: 3 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/EW10") |
| ![EMMY](/z-media/EMMY.png)<br>[Daytime Emmy Awards](/EMMY) (EMMY) | June 1980 to June 2012<br>Total: 119<br>Avg dur: 00:18:15<br>A: 116 (97%)<br>B: 2 (2%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/EMMY") |
| ![FHY](/z-media/FHY.png)<br>[The First Hundred Years](/FHY) (FHY) | January 1952 to January 1952<br>Total: 2<br>Avg dur: 00:14:25<br>A: 2 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/FHY") |
| ![GH](/z-media/GH.png)<br>[General Hospital](/GH) (GH) | January 1962 to October 2016<br>Total: 7770<br>Avg dur: 00:08:40<br>A: 7493 (96%)<br>B: 275 (4%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/GH") |
| ![GENR](/z-media/GENR.png)<br>[Generations](/GENR) (GENR) | January 1989 to January 1991<br>Total: 28<br>Avg dur: 00:14:30<br>A: 28 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/GENR") |
| ![GL](/z-media/GL.png)<br>[Guiding Light](/GL) (GL) | July 1952 to September 2009<br>Total: 972<br>Avg dur: 00:57:59<br>A: 892 (92%)<br>B: 79 (8%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/GL") |
| ![HFLS](/z-media/HFLS.png)<br>[Hawkins Falls](/HFLS) (HFLS) | October 1950 to April 1955<br>Total: 7<br>Avg dur: 00:13:22<br>A: 7 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/HFLS") |
| ![LL](/z-media/LL.png)<br>[Love of Life](/LL) (LL) | January 1953 to October 1982<br>Total: 27<br>Avg dur: 00:15:22<br>A: 26 (96%)<br>B: 1 (4%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/LL") |
| ![LMST](/z-media/LMST.png)<br>[Love is a Many Slendored Thing](/LMST) (LMST) | December 1967 to March 1973<br>Total: 5<br>Avg dur: 05:56:18<br>A: 5 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/LMST") |
| ![LVNG](/z-media/LVNG.png)<br>[Loving](/LVNG) (LVNG) | January 1983 to May 2009<br>Total: 102<br>Avg dur: 00:12:03<br>A: 85 (83%)<br>B: 17 (17%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/LVNG") |
| ![MSTR](/z-media/MSTR.png)<br>[Morning Star](/MSTR) (MSTR) | March 1966 to June 1966<br>Total: 5<br>Avg dur: 00:21:15<br>A: 5 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/MSTR") |
| ![OLTL](/z-media/OLTL.png)<br>[One Life To Live](/OLTL) (OLTL) | January 1968 to January 2017<br>Total: 2748<br>Avg dur: 01:08:14<br>A: 2369 (86%)<br>B: 369 (13%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/OLTL") |
| ![PP](/z-media/PP.png)<br>[Peyton Place](/PP) (PP) | September 1964 to June 1969<br>Total: 957<br>Avg dur: 00:13:14<br>A: 956 (100%)<br>B: 1 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/PP") |
| ![PC](/z-media/PC.png)<br>[Port Charles](/PC) (PC) | January 1997 to October 2003<br>Total: 1627<br>Avg dur: 00:20:54<br>A: 1622 (100%)<br>B: 3 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/PC") |
| ![RARE](/z-media/RARE.png)<br>[Rare Treasures](/RARE) (RARE) | September 1953 to June 1971<br>Total: 9<br>Avg dur: 00:15:33<br>A: 9 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/RARE") |
| ![RH](/z-media/RH.png)<br>[Ryan's Hope](/RH) (RH) | January 1975 to October 1989<br>Total: 210<br>Avg dur: 00:22:04<br>A: 135 (64%)<br>B: 75 (36%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/RH") |
| ![SB](/z-media/SB.png)<br>[Santa Barbara](/SB) (SB) | June 1984 to January 1992<br>Total: 317<br>Avg dur: 00:13:27<br>A: 312 (98%)<br>B: 5 (2%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/SB") |
| ![SFT](/z-media/SFT.png)<br>[Search For Tomorrow](/SFT) (SFT) | September 1951 to December 1986<br>Total: 245<br>Avg dur: 00:37:21<br>A: 223 (91%)<br>B: 21 (9%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/SFT") |
| ![SS](/z-media/SS.png)<br>[Secret Storm](/SS) (SS) | January 1955 to April 1973<br>Total: 19<br>Avg dur: 00:13:52<br>A: 16 (84%)<br>B: 3 (16%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/SS") |
| ![SSB](/z-media/SSB.png)<br>[Sunset Beach](/SSB) (SSB) | January 1997 to December 1998<br>Total: 30<br>Avg dur: 00:00:31<br>A: 6 (20%)<br>B: 24 (80%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/SSB") |
| ![SSET](/z-media/SSET.png)<br>[Summerset](/SSET) (SSET) | November 1972 to January 1973<br>Total: 2<br>Avg dur: 00:15:19<br>A: 1 (50%)<br>B: 1 (50%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/SSET") |
| ![TX](/z-media/TX.png)<br>[Texas](/TX) (TX) | January 1980 to January 1992<br>Total: 471<br>Avg dur: 00:50:38<br>A: 416 (88%)<br>B: 55 (12%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/TX") |
| ![VALL](/z-media/VALL.png)<br>[Valient Lady](/VALL) (VALL) | November 1953 to January 1955<br>Total: 5<br>Avg dur: 00:12:52<br>A: 5 (100%)<br>B: 0 (0%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/VALL") |
| ![YR](/z-media/YR.png)<br>[Young And The Restless](/YR) (YR) | January 1973 to January 2016<br>Total: 54<br>Avg dur: 00:01:09<br>A: 19 (35%)<br>B: 35 (65%)<br>[GitHub files]("https://github.com/HamiltonBernique/SoapJack/tree/main/YR") |


## How to watch videos

You can watch videos from this data in three ways.

### Copy the YouTube ID into the YouTube search bar

This method is the easiest. Copy the ID from the JSON data into the YouTube search bar. Select the video from the search results. If not in the results, construct a YouTube URL.

| Select ID from JSON data |
| --- |
| ![Select ID from JSON data](/z-media/z-selectid.png) |


### Construct a YouTube URL

Copy the ID from the JSON data and append to either of the following URLs, where `{id}` is the id placeholder.

- `https://youtu.be/{id}`
  Example: `https://youtu.be/p0Uiknmeg7g`
- `https://www.youtube.com/watch?v={id}`
  Example: `https://www.youtube.com/watch?v=p0Uiknmeg7g`

### Use a CSV file

Download the CSV file and import it into a spreadsheet, such as in a Google sheet or in Excel.

1. Select the CSV file in the repository and select **Download raw file** in the upper-right corner to download to your computer.
1. In a Google Sheet, select **Import** from the **File** menu and select the **Upload** tab to upload the CSV file from your computer. Set the **Import location** to replace the current sheet or desired option. Keep the `Convert text to numbers, dates, and formulas` option selected, as otherwise the YouTube link will not be operational.
   In the Excel desktop application, select **From Txt/Csv** from on the **Data** ribbon. In Excel online, simply open the fie.
1. After the import, you can select links in column A.

| Import a CSV file |
| --- |
| ![Import CSV file](/z-media/z-csvfile.png) |


## Contributions and corrections

Soap fans are encouraged to email feedback and corrections, or share an online spreadsheet from a CSV file, to `hamiltonbernique@icloud.com`.

If you have well formed JSON data to contribute, you're welcome to fork the repository and submit a pull request. The CSV files will be updated to reflect your contributions.
