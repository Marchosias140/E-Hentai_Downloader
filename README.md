# E-Hentai_Downloader
A python app that downloads galleries from e-hentai.org



Also, check out the new version




https://github.com/Marchosias140/E-Hentai_Downloader_Tankoboner_Edition















Instructions

This app is better run inside a Python environment, for better dependency management.



Run


```python3 E_Hentai_Downloader.py```



Follow the instructions on the terminal.






It is strongly adviced to only input links from the same gallery, unless you are sure that the names of the files are different, as if two files have the same name, the second will overwrite the first. 






After pasting the links, the app will download the images one by one by creating a temporal web browser instance that will close itself after the downloading process completes.







The downloaded images will be inside the Scraped_Images folder located in the same folder where the app was executed.




It is strongly adviced to immediatly change the name of the Scrapped_Images folder in order to avoid having the images overwritten if another gallery is downloaded right after, thus another Scraped_Images folder will be created and your previous files will be intact.



The app cleans itself from the pasted links by creating new link processor files and erasing all text files, thus the app is ready to be used again.




The dependencies needed are:

- selenium

- requests

- bs4




Have fun!






