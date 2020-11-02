# find47-image-url-lindex
Find 47,  https://find47.jp/ index of image urls

## TBD
This repository includes only 2 CSV files.
 - 01.csv - with simplified information. Areas(0-7), Prefectures(0-46), Unique file index and maximum size of provided images (xl, l, m or s).
 - 02.csv - generated from 01.csv to provide just 2 rows for downloading, URL and ./hpg/something.zip to be downloaded on local storage. 
It will be easy to use 02.csv to download images from https://find47.jp/ by the help of wget or "urllib.request.urlretrieve(dl_from, dl_to)" in Python3 script.
