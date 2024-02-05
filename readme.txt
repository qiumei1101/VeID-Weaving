%******************************************************************************************************************%
% The VeID-INDOT-Weaving dataset is collected with 20 cameras in Indiana highways, USA.                    %
% A total of 776 vehicles are annotated. 200 vehicles are used for testing. The remaining 576 vehicles are 		   %
% for testing.                                                                                                     %
% There are 11579 images in the test set, and 37778 images in the training set.                                    %
% If you use this dataset, please kindly cite our paper as,                                                        %
%                                                                                                                  %
% This dataset should be used for research only. Please DO NOT distribute or use it for commercial purpose.        %
%******************************************************************************************************************%

Content in the directory:
1. "image_query/". This dir contains 1678 images as queries.
2. "image_test/". This dir contains 11579 images for testing.
3. "image_train/". This dir contains 37778 images for training.
4. "name_query.txt". It lists all query file names.
5. "name_test.txt". It lists all test file names.
6. "name_train.txt". It lists all train file names.
7. "test_track.txt". It records all test tracks. Each track contrains about 6 images of the same vehicle captured by one camera at a time.
8. "gt_image.txt". It lists the ground truths of each query in each line.
10. "train_label.xml". It lists the labels, e.g., vehicle ID, camera ID, color, type, of the training images.
11. "test_label.xml". It lists the labels of all test images.
14. "camera_ID.txt". It lists the IDs of all 20 cameras.

If you have any problem, please contact meiqiu@iu.edu
