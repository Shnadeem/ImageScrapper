# ImageScrapper
This utility is to download the images in bulk. Below are the steps to execute the same.

## Execution
#1. Create project in PyCharm with conda (virtual environment) python 3.8
#2. download the files and folder structure as given here. Place it at home folder of your new vertual environment
#3. Open terminal of this new environment and run requirements.txt file (pip install -r requirements.txt)
#4. Default configurations:
# 4.1 Seach: Dog
# 4.2 Limit: 5
#5. Below are syntax to be executed for this code to run
# 5.1 With default parameter
#     python image.py
# 5.2 With override parameter
#     python image.py -s Cat -l 10  (download 10 images of Cat)
# Sample Execution
#   (imageScrapper) E:\Python\iNeuron\Scrapper\Image\imageScrapper>python image.py -l 10 -s Lion
#   ./image/Lion/ Directory created successfully
#   10 images of Lion downloaded successfully.
