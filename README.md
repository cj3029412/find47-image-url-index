# find47-image-url-index
Find 47,  https://find47.jp/ index of image urls for published 1080 images (as of 2nd Nov 2020) there with each maximum resolution. 

## Summary
This repository includes only 2 CSV files.
 - 01.csv - with simplified information. Areas(0-7), Prefectures(0-46), Unique file index and maximum size of provided images (xl, l, m or s).
 - 02.csv - generated from 01.csv to provide just 2 columns for downloading purpose, URL and ./jpg/something.zip to be downloaded on local storage. 
It will be easy to use 02.csv to download images from https://find47.jp/ by the help of wget or "urllib.request.urlretrieve(dl_from, dl_to)" in Python3 script.

## Notes
 When using 02.csv to download total 1080 images at each maximum size defined in the csv, around 10GB of storage space will be taken with only jpg image files even afrer extracting, removing zip and attached text.
 Also, it will take one night to all the images to be downloaded with enough waiting seconds to minimize find/47 server load.
