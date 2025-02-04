# The SoapJack Project

The SoapJack Project is to create a catalog of YouTube classic soap opera videos organized by their original air dates as much as possible. Data is provided in JSON and CSV formats. For questions and feedback, email Bruce Hamilton at `hamiltonbernique@icloud.com`

To watch a video from the data, copy the id from the JSON data into the YouTube search bar. Or you can construct the URL in in two ways:

- `https://youtu.be/{id}`
- `https://www.youtube.com/watch?v={id}`

Column A in the CSV files has the id formatted into a link that will take you right to YouTube. In a Google Sheet, be sure to select Import from the File menu and have `Convert to numbers, text, and formulas` selected.

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

Categories:
A = Episodes and clips
B = Promos, open/closings
| Soap Opera | Stats
| --- | --- |
| ![AMC](/z-media/AMC.png)<br>[All My Children](/AMC) (AMC) | 01 1970 to 01 1970<br>Total: 5333, avg dur: 00:18:50<br>A: 5073 (95.124695%)<br>B: 258 (4.837802%) |
| ![ATWT](/z-media/ATWT.png)<br>[As The World Turns](/ATWT) (ATWT) | 04 1957 to 04 1957<br>Total: 644, avg dur: 01:07:17<br>A: 573 (88.975155%)<br>B: 71 (11.024845%) |
| ![AW](/z-media/AW.png)<br>[Another World](/AW) (AW) | 05 1964 to 05 1964<br>Total: 3888, avg dur: 09:37:34<br>A: 3808 (97.942387%)<br>B: 80 (2.057613%) |
| ![BB](/z-media/BB.png)<br>[Bold And The Beautiful](/BB) (BB) | 01 1989 to 01 1989<br>Total: 56, avg dur: 00:05:32<br>A: 17 (30.357143%)<br>B: 39 (69.642857%) |
| ![BDAY](/z-media/BDAY.png)<br>[The Brighter Day](/BDAY) (BDAY) | 01 1955 to 01 1955<br>Total: 4, avg dur: 00:14:29<br>A: 4 (100.000000%)<br>B: 0 (0.000000%) |
| ![CITY](/z-media/CITY.png)<br>[The City](/CITY) (CITY) | 01 1991 to 01 1991<br>Total: 28, avg dur: 00:20:25<br>A: 27 (96.428571%)<br>B: 1 (3.571429%) |
| ![CPTL](/z-media/CPTL.png)<br>[Capitol](/CPTL) (CPTL) | 01 1982 to 01 1982<br>Total: 124, avg dur: 00:20:06<br>A: 121 (97.580645%)<br>B: 3 (2.419355%) |
| ![DAYS](/z-media/DAYS.png)<br>[Days Of Our Lives](/DAYS) (DAYS) | 11 1965 to 11 1965<br>Total: 71, avg dur: 00:04:34<br>A: 26 (36.619718%)<br>B: 45 (63.380282%) |
| ![DCTR](/z-media/DCTR.png)<br>[The Doctors](/DCTR) (DCTR) | 12 1967 to 12 1967<br>Total: 21, avg dur: 00:04:57<br>A: 15 (71.428571%)<br>B: 6 (28.571429%) |
| ![EDGE](/z-media/EDGE.png)<br>[The Edge Of Night](/EDGE) (EDGE) | 01 1955 to 01 1955<br>Total: 504, avg dur: 00:18:28<br>A: 485 (96.230159%)<br>B: 19 (3.769841%) |
| ![EGG](/z-media/EGG.png)<br>[The Egg and I](/EGG) (EGG) | 01 1951 to 01 1951<br>Total: 2, avg dur: 00:13:41<br>A: 2 (100.000000%)<br>B: 0 (0.000000%) |
| ![EW10](/z-media/EW10.png)<br>[Emergency Ward 10](/EW10) (EW10) | 08 1958 to 08 1958<br>Total: 3, avg dur: 00:20:14<br>A: 3 (100.000000%)<br>B: 0 (0.000000%) |
| ![EMMY](/z-media/EMMY.png)<br>[Daytime Emmy Awards](/EMMY) (EMMY) | 06 1980 to 06 1980<br>Total: 119, avg dur: 00:18:15<br>A: 116 (97.478992%)<br>B: 2 (1.680672%) |
| ![FHY](/z-media/FHY.png)<br>[The First Hundred Years](/FHY) (FHY) | 01 1952 to 01 1952<br>Total: 2, avg dur: 00:14:25<br>A: 2 (100.000000%)<br>B: 0 (0.000000%) |
| ![GH](/z-media/GH.png)<br>[General Hospital](/GH) (GH) | 01 1962 to 01 1962<br>Total: 7770, avg dur: 00:08:40<br>A: 7493 (96.435006%)<br>B: 275 (3.539254%) |
| ![GENR](/z-media/GENR.png)<br>[Generations](/GENR) (GENR) | 01 1989 to 01 1989<br>Total: 28, avg dur: 00:14:30<br>A: 28 (100.000000%)<br>B: 0 (0.000000%) |
| ![GL](/z-media/GL.png)<br>[Guiding Light](/GL) (GL) | 07 1952 to 07 1952<br>Total: 972, avg dur: 00:57:59<br>A: 892 (91.769547%)<br>B: 79 (8.127572%) |
| ![HFLS](/z-media/HFLS.png)<br>[Hawkins Falls](/HFLS) (HFLS) | 10 1950 to 10 1950<br>Total: 7, avg dur: 00:13:22<br>A: 7 (100.000000%)<br>B: 0 (0.000000%) |
| ![LL](/z-media/LL.png)<br>[Love of Life](/LL) (LL) | 01 1953 to 01 1953<br>Total: 27, avg dur: 00:15:22<br>A: 26 (96.296296%)<br>B: 1 (3.703704%) |
| ![LMST](/z-media/LMST.png)<br>[Love is a Many Slendored Thing](/LMST) (LMST) | 12 1967 to 12 1967<br>Total: 5, avg dur: 05:56:18<br>A: 5 (100.000000%)<br>B: 0 (0.000000%) |
| ![LVNG](/z-media/LVNG.png)<br>[Loving](/LVNG) (LVNG) | 01 1983 to 01 1983<br>Total: 102, avg dur: 00:12:03<br>A: 85 (83.333333%)<br>B: 17 (16.666667%) |
| ![MSTR](/z-media/MSTR.png)<br>[Morning Star](/MSTR) (MSTR) | 03 1966 to 03 1966<br>Total: 5, avg dur: 00:21:15<br>A: 5 (100.000000%)<br>B: 0 (0.000000%) |
| ![OLTL](/z-media/OLTL.png)<br>[One Life To Live](/OLTL) (OLTL) | 01 1968 to 01 1968<br>Total: 2748, avg dur: 01:08:14<br>A: 2369 (86.208151%)<br>B: 369 (13.427948%) |
| ![PP](/z-media/PP.png)<br>[Peyton Place](/PP) (PP) | 09 1964 to 09 1964<br>Total: 957, avg dur: 00:13:14<br>A: 956 (99.895507%)<br>B: 1 (0.104493%) |
| ![PC](/z-media/PC.png)<br>[Port Charles](/PC) (PC) | 01 1997 to 01 1997<br>Total: 1627, avg dur: 00:20:54<br>A: 1622 (99.692686%)<br>B: 3 (0.184388%) |
| ![RARE](/z-media/RARE.png)<br>[Rare Treasures](/RARE) (RARE) | 09 1953 to 09 1953<br>Total: 9, avg dur: 00:15:33<br>A: 9 (100.000000%)<br>B: 0 (0.000000%) |
| ![RH](/z-media/RH.png)<br>[Ryan's Hope](/RH) (RH) | 01 1975 to 01 1975<br>Total: 210, avg dur: 00:22:04<br>A: 135 (64.285714%)<br>B: 75 (35.714286%) |
| ![SB](/z-media/SB.png)<br>[Santa Barbara](/SB) (SB) | 06 1984 to 06 1984<br>Total: 317, avg dur: 00:13:27<br>A: 312 (98.422713%)<br>B: 5 (1.577287%) |
| ![SFT](/z-media/SFT.png)<br>[Search For Tomorrow](/SFT) (SFT) | 09 1951 to 09 1951<br>Total: 245, avg dur: 00:37:21<br>A: 223 (91.020408%)<br>B: 21 (8.571429%) |
| ![SS](/z-media/SS.png)<br>[Secret Storm](/SS) (SS) | 01 1955 to 01 1955<br>Total: 19, avg dur: 00:13:52<br>A: 16 (84.210526%)<br>B: 3 (15.789474%) |
| ![SSB](/z-media/SSB.png)<br>[Sunset Beach](/SSB) (SSB) | 01 1997 to 01 1997<br>Total: 30, avg dur: 00:00:31<br>A: 6 (20.000000%)<br>B: 24 (80.000000%) |
| ![SSET](/z-media/SSET.png)<br>[Summerset](/SSET) (SSET) | 11 1972 to 11 1972<br>Total: 2, avg dur: 00:15:19<br>A: 1 (50.000000%)<br>B: 1 (50.000000%) |
| ![TX](/z-media/TX.png)<br>[Texas](/TX) (TX) | 01 1980 to 01 1980<br>Total: 471, avg dur: 00:50:38<br>A: 416 (88.322718%)<br>B: 55 (11.677282%) |
| ![VALL](/z-media/VALL.png)<br>[Valient Lady](/VALL) (VALL) | 11 1953 to 11 1953<br>Total: 5, avg dur: 00:12:52<br>A: 5 (100.000000%)<br>B: 0 (0.000000%) |
| ![YR](/z-media/YR.png)<br>[Young And The Restless](/YR) (YR) | 01 1973 to 01 1973<br>Total: 54, avg dur: 00:01:09<br>A: 19 (35.185185%)<br>B: 35 (64.814815%) |



