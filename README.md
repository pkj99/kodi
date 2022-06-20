# kodi Media Center Database Restore Procedure

1. Download MOVIE.zip TVSHOW.zip videodb.zip to /storage/emulated/0/Download
2. Extract all of them to current path, then you will see

    * MOVIE
    * TVSHOW
    * videodb.xml
	
3. import videodb.xml from KODI

that's it.

or you can download full set MEDIADB.zip for easy restoration


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



How to install Netflix skin with Chinese fonts enabled

1. install repository.titan.bingie.mod-1.0.0.zip
2. cancel enabling BINGIE skin first
3. manually install skin.titan.bingie.mod-matrix.zhtw.zip
4. change look and feel to BINGIE netflix skin
