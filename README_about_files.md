##### Following files were not pushed to git due to size limitations
1. `resources` folder containing detections and networks. Download from [here](https://drive.google.com/drive/folders/18fKzfqnqhqW3s9zwsCbnVJ5XF2JFeqMp).
2. `MOT16` folder containing video sequences downloadable from [here](https://motchallenge.net/data/MOT16/).

##### Find files that are greater than 95 MB
`find /Users/ajaymaity/Documents/gits/deep_sort/ -type f -size +95000k -exec ls -lh {} \; | awk '{ print $9 ": " $5 }'`
