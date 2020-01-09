# generate-dataset
In the case that you do not have dataset that you desire for your machine learning module particularly for image processing you can programmatically download images examples of any kind via APIs on varying platforms.
Exactly which API you choose here depends on example of images you are attempting to gather.
Best option would be to leverage a search engine, such as Google or Bing:
Using this py program you can use Google Images to somewhat manually and somewhat programmatically download example images for a given query.
A better option would be to use Bing’s Image Search API which is fully automatic and does not require manual intervention. 

Run this program in cammand prompt using following command:
python genrate_dataset.py --query "example_image name" --output dataset/example_image title

An example command for downloading face images via the Bing Image Search API for the character, Robert Downey is as follow:
python genrate_dataset.py --query "Robert Downey" --output dataset/Robert Downey
