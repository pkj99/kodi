# kodi Media Center Database Restore Procedure

1. Download MEDIADB.zip and videodb.zip to /storage/emulated/0/Download
2. Extract all of them to current path, then you will see

    * MOVIE
    * TVSHOW
	* MV
    * videodb.xml
	
3. import videodb.xml into KODI database
4. add MOVIE, TVSHOW and MV source and setup scrape api for future update

that's it.

ps. default media location:

	* videodb.zip		: /storage/emulated/0/Download
	* videodb4pc.zip 	: E:\


<< changeKodiVideodbPath >>

usage: changeKodiVideodbPath.exe [-h] [-m MODE] [-i INPUT] [-o OUTPUT] [-s SOURCE] [-d DESTINATION]

      options:

      -h, --help                                    show this help message and exit
 
      -m MODE, --mode MODE                          PC2PC. PC2TV, TV2TV or TV2PC
 
      -i INPUT, --input INPUT                       input file name videodb.xml 
 
      -o OUTPUT, --output OUTPUT                    output file name if given (default:overwrite)
 
      -s SOURCE, --source SOURCE                    source path (default: E:\)
 
      -d DESTINATION, --destination DESTINATION     destination path
 
Example: if you want to use Kodi in PC, you can replace folder string (/storage/emulated/0/Download) in videodb.xml to your allocated path (E:)

      E:\MOVIE E:\TVSHOW
      
      changeKodiVideodbPath -m TV2PC -i videodb.xml [-o videodb2.xml] -s /storage/emulated/0/Download -d E:
	  
	  or (swap)
	  
	  changeKodiVideodbPath -m PC2TV -i videodb.xml -o videodb2.xml -s E: -d /storage/emulated/0/Download



How to install Netflix skin with Chinese fonts enabled

1. install repository.titan.bingie.mod-1.0.0.zip
2. cancel enabling BINGIE skin first
3. manually install skin.titan.bingie.mod-matrix.zhtw.zip
4. change look and feel to BINGIE netflix skin


![alt text](https://github.com/pkj99/kodi/blob/master/images/tips/netflix.skin.installation.mp4_snapshot_00.13.257.jpg?raw=true)