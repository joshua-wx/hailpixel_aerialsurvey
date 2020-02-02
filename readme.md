##HailPixel Toolkit

###Additional software needed
- [mask-rcnn](https://github.com/matterport/Mask_RCNN)
- [VIA annotation software](https://www.google.com/search?hl=en&q=VIA%20annotation)

#Steps
0. Fly hail swath immediately after hailfall. Ideally at 10 m altitude over a 50x50 m area. Can be done in manual flight mode or using a survey app like Pix4D, just ensure overlap is > 70% and pick an area that is very well covered with short, mowen grass.
1. Generate orthomoasic tif from aerial imagery using software like Agisoft metapixel (use high setting)
2. Run generate_subset script for each orthomoasic to generate subsets for processing.
3. Manually inspect subsets to remove and images with non-hail features and image distortion.
4. Mask-RCNN
5. Measurement + stats
