# Kodi Media Center userdata Restore Procedure

1. Download https://github.com/pkj99/kodi/raw/master/mediadb/MEDIADB.zip to /storage/emulated/0/Download 
2. Download https://github.com/pkj99/kodi/raw/master/userdata/TV/userdata.zip to /storage/emulated/0/Download

	* NAS:		smb://192.168.1.1/g
	* PC:		E:\
	* TV:		/storage/emulated/0/Download
	
3. Extract all of them to current path, then you will see

    * MOVIE
    * TVSHOW
    * userdata
	
4. open file manager on Kodi
5. left-side create source to /storage/emulated/0/Download/userdata
6. right-side choose current userdata directory
7. from left-side select all and copy to right-side
8. exit Kodi and open it again

that's it.

# userdata directory explanation

	<addon_data>			settings of installed add-ons
	<Database>			media db
		Addons33.db
		Epg13.db		TV epg information
		MyMusic82.db
		MyVideos119.db		media database including all information of movies and tv shows
		Textures13.db
		TV38.db			TV channels
		ViewModes6.db
	<playlists>			playlists (eg. musicvideo)
	favourites.xml
	guisettings.xml
	profiles.xml
	RssFeeds.xml
	sources.xml			media path
	

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.1.png?raw=true)

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.2.png?raw=true)

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.3.png?raw=true)

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.4.png?raw=true)

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.5.png?raw=true)

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.6.png?raw=true)

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.7.png?raw=true)

![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/userdata.restore.procedure.8.png?raw=true)
