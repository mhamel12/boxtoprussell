# boxtoprussell
Box scores from the career of Bill Russell with the Boston Celtics

This project began many years ago, before the Basketball-Reference.com site included NBA box scores. I am storing these files on Github for future safe-keeping.
The data in this folder corresponds to Version 3.8 of Bill Russell era-archive that I posted on June 29, 2014 at https://michaelhamel.net/boxtop-russell/

HISTORY

When I began research for my book, Rising Above the Rim, in 2007, I was struck by the lack of an online repository for NBA box scores. David Smith and his fellow volunteers had built Retrosheet.org into an extremely valuable research tool for Major League Baseball box scores and play-by-play accounts, and I had naively assumed that a basketball equivalent existed. However, there was little available beyond some limited efforts on scattered web sites, such as Basketball-Reference.com. So, to collect the box scores I needed for Rising Above the Rim, I turned to the microfilm machines at the Boston Public Library, along with some additional sources such as Bill Woten’s excellent book Game 7. I figured it would take months to assemble a more complete collection, based on the demands of my real job.

Then, in the spring of 2010, my local library announced they had obtained access to an online archive of Boston Globe articles for the years prior to 1980. I realized immediately that these .pdf’s would include box scores, so I stopped work on another project I was pursuing and began downloading Celtics articles from the “Bill Russell era” – 1956 through 1969.

But there were some problems. Many box scores were missing, especially late night games on the West Coast, and the quality of the ones that were available varied – most were basic versions that contained only FGM, FTM, FTA, PF, and PTS, while others were complete with REB, AST, etc. There were also plenty of typographical errors and blurred images. I began to contact a few folks looking for additional sources, privately dreading the prospect of having to spend hours digging through other Boston newspapers on microfilm before being able to post an initial version.

Fortunately, Richard Johnson, curator of The Sports Museum in Boston, graciously responded to an email with a suggestion to look at Celtics yearbooks from the era. These contained box scores of every game, and even though they were mostly basic in nature, they provided an important second source and were invaluable to my research.

Then in January 2012, basketball-reference.com announced that they were posting Dick Pfander’s collection of box score clippings for every game in NBA history. That collection helped fill in more gaps, but the box scores here at Rising Above the Rim are superior in three ways:

1. BOXTOP data is available in raw .csv format for automated analysis
2. BOXTOP box scores are based on data from multiple sources, which helps improve their completeness and accuracy
3. I publish a report for each season that lists all known inconsistencies in the data, including cross-checks against Celtics team statistics

Since then, the NBA has also posted box scores going back to 1946-47 at their website here: http://stats.nba.com/scores.html?ls=iref:nba:gnav

Also note that, beginning with the 1966-67 season, the collection at basketball-reference.com is taken directly from The Sporting News archive available at Paper of Record.

NOTE ON THE DATA HERE

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License. To view a copy of this license, visit # http://creativecommons.org/licenses/by-nc-sa/3.0/ or send a letter to Creative Commons, 171 Second Street, Suite 300, San Francisco, California, 94105, USA.

If you use this data, you must include the following statement:

The information used here was obtained free of charge from and is copyrighted by the Basketball BOXTOP Project.

This data is presented AS IS, with no guarantee of accuracy (in fact, there are definitely errors in the data, and known problems are listed within the data set itself). Interested parties may contact “michael {dot} hamel {at} gmail {dot} com” for more information or if they wish to help improve the quality or scope of the data.

BOXTOP format

The BOXTOP format is loosely based on Retrosheet’s “Box Score Event Files” (BSEF) format, which is essentially a comma-separated file (.csv) format. More details are included in the .zip archive. Several perl scripts have been written to make data entry faster and to verify the box scores for accuracy. Each box score is checked for internal consistency, such as whether (FGM * 2) + FTM = the number of points scored, and then the entire season is checked for consistency of the Boston Celtics data, since I only have Celtics box scores at this point. All errors reported by these scripts are included in the Report files available above. Examples of the tools are included in the .zip archive.

CONTRIBUTORS

Matthew Shuh


MAJOR REFERENCES

Boston Celtics Yearbooks

Boston Globe, Boston Herald, Boston Record-American

New York Times

The Sporting News at Paper of Record (free for SABR members)

Basketball-Reference.com

Game 7 by Bill Woten

NBA Referees
http://www.nbahoopsonline.com/History/Year/refs/index.html

NBA Referees on apbr.org
http://apbr.org/forum/viewtopic.php?p=14021

NBA Referees 1946-
http://www.phillyref.com/basketball/nbarefs/nbarefhistory.html

NBA Finals Box Scores
http://webuns.chez-alice.fr/home.htm

NBAStats.net
