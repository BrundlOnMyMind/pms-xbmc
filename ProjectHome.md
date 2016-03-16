# Thanks for stopping by #
Please leave comments and suggestions in the wiki/issues/[PS3 Media Server Forum](http://www.ps3mediaserver.org/forum/viewtopic.php?f=12&t=13338)
<p>
<br>
</p>
# About #
XBMC is awesome for playing media, as well as scraping all the nice meta data for it.

Now XBMC can act as a UPNP server but it does not show all the meta data on the client. This is where PS3 Media Server comes in. PMS is a DLNA Server. Unfortunately it does not have a nice way of sorting and displaying your data other than the folder structure on the file system.

This Plugin is for PS3 Media Server, and it uses the video database created by XBMC and displays it in a much friendlier way on any DLNA client along with all the movie info

## LATEST RELEASE 2013-05-03 ##
Update:
  * Added Sets category (thanks Anil)
  * Added an "All" item to movie titles so all movies can be listed in one go
  * Compiled against the latest PMS(v1.80) and XBMC(v12.1)

# Installation #

Grab the jars from the downloads page (pms-xbmc-xxxxxxxx.jar, and sqlitejdbc-v056.jar or mysql-connector-java-5.1.18-bin.jar if using mysql) and drop them in PMS's plugin directory
start PMS, and go to the plugin's config.
  * If you are using a MySQL database for XBMC click on the Config button and fill in the details as in your advancedsettings.xml.
  * If you are using the default database settings in XBMC, click on the  browse button and locate the XBMC sqlite database and select the video db file.
save the config and restart PMS.
When browsing your media you will notice a new folder in the root where all the XBMC media will be in

# Discussion #
[PS3 Media Server Forum](http://www.ps3mediaserver.org/forum/viewtopic.php?f=12&t=13338&sid=d5084ff2aafab5380594c5eddf2748b5)

# Features #

Sorts your videos exactly the same way as XBMC does, ie: Movies, TV Shows, Title, Genre, Year, (more to come)

Access music in your XBMC music library

Connectivity to an XBMC MySQL database. (no music support yet)

Displays the following for each title (if available):
  * Name,
  * Tagline,
  * Running Time,
  * Age Restriction,
  * Genre,
  * Sinopsis,
  * Director,
  * Writer,
  * IMDB Rating,
  * Country,
  * Studio,
  * Video CODEC,
  * Video Size,
  * Audio CODEC,
  * Audio Channels,
  * Season/Episode,
  * Watched count (sort of),
  * Fanart (Only as icon),
  * Posters (only the icon),
  * Reset watched count,