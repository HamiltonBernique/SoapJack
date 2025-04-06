# The SoapJack Project

The purpose of the SoapJack Project is to create a catalog of YouTube classic soap opera video links organized by their original air dates. Data is provided in JSON and CSV formats. For questions and feedback, email Bruce Hamilton at `hamiltonbernique@icloud.com`. 

There are currently over 26,000 links in the repository. The repository is organized alphabetically by the soap opera codes as listed in the next section below. Each folder has JSON and CSV files.
 
Such a dataset is indeed malleable and loosely defined. The goal is an inventory of those classic soap operas that aired from the 1950s to the 2010s. This time period essentially spans the time when no content was not saved except by the efforts of the devoted fans who later uploaded their treasures to YouTube. Some soaps are commercially available in their entirety such as Dark Shadows, so those soaps are not included. 

The data has the following criteria, but your input in more than welcome:

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
| duration | The length of the video obtained from YouTube. |
| channel | The YouTube channel that hosts the video. The HamiltonBernique Project is very appreciative of the fine work these soap fans have made, for without them this history making would not be possible. Visit the [HamiltonBernique](https://www.youtube.com/@HamiltonBernique) YouTube channel for All My Children and One Life to Live videos. |

See [How to watch videos](#how-to-watch-videos).

## Soap Operas

Categories:
A = Episodes and clips

B = Promos, open/closings

C = Emmys

| Soap Opera | Stats
| --- | --- |
| **All My Children** (AMC)<br>![AMC](/z-media/AMC.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/AMC) | February 1970 to January 2017<br>Total: 5,687<br>Episodes and clips: 5,419 (95%)<br>Open/Close, promos: 268 (5%) |
| **As The World Turns** (ATWT)<br>![ATWT](/z-media/ATWT.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/ATWT) | April 1957 to September 2010<br>Total: 658<br>Episodes and clips: 573 (87%)<br>Open/Close, promos: 85 (13%) |
| **Another World** (AW)<br>![AW](/z-media/AW.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/AW) | May 1964 to July 2002<br>Total: 3,983<br>Episodes and clips: 3,850 (97%)<br>Open/Close, promos: 133 (3%) |
| **Bold And The Beautiful** (BB)<br>![BB](/z-media/BB.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/BB) | January 1987 to September 2010<br>Total: 63<br>Episodes and clips: 17 (27%)<br>Open/Close, promos: 46 (73%) |
| **The Brighter Day** (BDAY)<br>![BDAY](/z-media/BDAY.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/BDAY) | January 1955 to January 1960<br>Total: 4<br>Episodes and clips: 4 (100%)<br>Open/Close, promos: 0 (0%) |
| **The City** (CITY)<br>![CITY](/z-media/CITY.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/CITY) | January 1991 to February 1997<br>Total: 30<br>Episodes and clips: 27 (90%)<br>Open/Close, promos: 3 (10%) |
| **Capitol** (CPTL)<br>![CPTL](/z-media/CPTL.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/CPTL) | January 1980 to March 1987<br>Total: 131<br>Episodes and clips: 121 (92%)<br>Open/Close, promos: 10 (8%) |
| **Days Of Our Lives** (DAYS)<br>![DAYS](/z-media/DAYS.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/DAYS) | November 1965 to October 2019<br>Total: 143<br>Episodes and clips: 28 (20%)<br>Open/Close, promos: 115 (80%) |
| **The Doctors** (DCTR)<br>![DCTR](/z-media/DCTR.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/DCTR) | December 1967 to January 1982<br>Total: 24<br>Episodes and clips: 15 (62%)<br>Open/Close, promos: 9 (38%) |
| **The Edge Of Night** (EDGE)<br>![EDGE](/z-media/EDGE.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/EDGE) | January 1955 to December 1984<br>Total: 509<br>Episodes and clips: 485 (95%)<br>Open/Close, promos: 24 (5%) |
| **The Egg and I** (EGG)<br>![EGG](/z-media/EGG.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/EGG) | January 1951 to March 1952<br>Total: 2<br>Episodes and clips: 2 (100%)<br>Open/Close, promos: 0 (0%) |
| **Emergency Ward 10** (EW10)<br>![EW10](/z-media/EW10.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/EW10) | August 1958 to August 1959<br>Total: 3<br>Episodes and clips: 3 (100%)<br>Open/Close, promos: 0 (0%) |
| **Daytime Emmy Awards** (EMMY)<br>![EMMY](/z-media/EMMY.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/EMMY) | January 1978 to June 2012<br>Total: 147<br>Episodes and clips: 0 (0%)<br>Open/Close, promos: 3 (2%) |
| **The First Hundred Years** (FHY)<br>![FHY](/z-media/FHY.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/FHY) | January 1952 to January 1952<br>Total: 2<br>Episodes and clips: 2 (100%)<br>Open/Close, promos: 0 (0%) |
| **General Hospital** (GH)<br>![GH](/z-media/GH.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/GH) | January 1962 to October 2016<br>Total: 7,782<br>Episodes and clips: 7,494 (96%)<br>Open/Close, promos: 286 (4%) |
| **Generations** (GENR)<br>![GENR](/z-media/GENR.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/GENR) | January 1989 to January 1991<br>Total: 29<br>Episodes and clips: 28 (97%)<br>Open/Close, promos: 1 (3%) |
| **Guiding Light** (GL)<br>![GL](/z-media/GL.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/GL) | July 1952 to September 2009<br>Total: 983<br>Episodes and clips: 893 (91%)<br>Open/Close, promos: 90 (9%) |
| **Hawkins Falls** (HFLS)<br>![HFLS](/z-media/HFLS.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/HFLS) | October 1950 to April 1955<br>Total: 7<br>Episodes and clips: 7 (100%)<br>Open/Close, promos: 0 (0%) |
| **Love of Life** (LL)<br>![LL](/z-media/LL.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/LL) | January 1953 to October 1982<br>Total: 28<br>Episodes and clips: 26 (93%)<br>Open/Close, promos: 2 (7%) |
| **Love is a Many Splendored Thing** (LMST)<br>![LMST](/z-media/LMST.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/LMST) | December 1967 to March 1973<br>Total: 5<br>Episodes and clips: 5 (100%)<br>Open/Close, promos: 0 (0%) |
| **Loving** (LVNG)<br>![LVNG](/z-media/LVNG.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/LVNG) | January 1983 to May 2009<br>Total: 106<br>Episodes and clips: 85 (80%)<br>Open/Close, promos: 21 (20%) |
| **Morning Star** (MSTR)<br>![MSTR](/z-media/MSTR.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/MSTR) | March 1966 to June 1966<br>Total: 5<br>Episodes and clips: 5 (100%)<br>Open/Close, promos: 0 (0%) |
| **One Life To Live** (OLTL)<br>![OLTL](/z-media/OLTL.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/OLTL) | January 1967 to January 2017<br>Total: 3,016<br>Episodes and clips: 2,634 (87%)<br>Open/Close, promos: 382 (13%) |
| **Peyton Place** (PP)<br>![PP](/z-media/PP.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/PP) | September 1964 to June 1969<br>Total: 957<br>Episodes and clips: 956 (100%)<br>Open/Close, promos: 1 (0%) |
| **Port Charles** (PC)<br>![PC](/z-media/PC.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/PC) | January 1997 to October 2003<br>Total: 1,627<br>Episodes and clips: 1,624 (100%)<br>Open/Close, promos: 3 (0%) |
| **Rare Treasures** (RARE)<br>![RARE](/z-media/RARE.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/RARE) | September 1953 to June 1971<br>Total: 9<br>Episodes and clips: 9 (100%)<br>Open/Close, promos: 0 (0%) |
| **Ryan's Hope** (RH)<br>![RH](/z-media/RH.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/RH) | January 1975 to October 1989<br>Total: 690<br>Episodes and clips: 609 (88%)<br>Open/Close, promos: 81 (12%) |
| **Santa Barbara** (SB)<br>![SB](/z-media/SB.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/SB) | January 1984 to January 1993<br>Total: 439<br>Episodes and clips: 380 (87%)<br>Open/Close, promos: 59 (13%) |
| **Search For Tomorrow** (SFT)<br>![SFT](/z-media/SFT.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/SFT) | September 1951 to December 1986<br>Total: 251<br>Episodes and clips: 223 (89%)<br>Open/Close, promos: 27 (11%) |
| **Secret Storm** (SS)<br>![SS](/z-media/SS.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/SS) | January 1955 to April 1973<br>Total: 19<br>Episodes and clips: 16 (84%)<br>Open/Close, promos: 3 (16%) |
| **Sunset Beach** (SSB)<br>![SSB](/z-media/SSB.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/SSB) | January 1997 to December 1998<br>Total: 30<br>Episodes and clips: 6 (20%)<br>Open/Close, promos: 24 (80%) |
| **Summerset** (SSET)<br>![SSET](/z-media/SSET.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/SSET) | November 1972 to January 1973<br>Total: 2<br>Episodes and clips: 1 (50%)<br>Open/Close, promos: 1 (50%) |
| **Texas** (TX)<br>![TX](/z-media/TX.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/TX) | January 1980 to January 1992<br>Total: 471<br>Episodes and clips: 416 (88%)<br>Open/Close, promos: 55 (12%) |
| **Valient Lady** (VALL)<br>![VALL](/z-media/VALL.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/VALL) | November 1953 to January 1955<br>Total: 5<br>Episodes and clips: 5 (100%)<br>Open/Close, promos: 0 (0%) |
| **Young And The Restless** (YR)<br>![YR](/z-media/YR.webp)<br>[GitHub files](https://github.com/HamiltonBernique/SoapJack/tree/main/YR) | January 1973 to January 2016<br>Total: 81<br>Episodes and clips: 20 (25%)<br>Open/Close, promos: 61 (75%) |


## How to watch videos

You can watch videos from this data in three ways.

### Copy the YouTube ID into the YouTube search bar

This method is the easiest. Copy the ID from the JSON data into the YouTube search bar. Select the video from the search results. If not in the results, construct a YouTube URL.

| Select ID from JSON data |
| --- |
| ![Select ID from JSON data](/z-media/z-selectid.webp) |


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
| ![Import CSV file](/z-media/z-csvfile.webp) |


## Contributions and corrections

Soap fans are encouraged to email feedback, and corrections, or share an online spreadsheet with your edits, to:
Bruce Hamilton
`bruce@hamiltonbernique.com`.

Always eager to know about new channels with soap opera content.

If you have well formed JSON data to contribute, you're welcome to fork the repository and submit a pull request. The CSV files will be updated to reflect your contributions.
