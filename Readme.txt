Open the Dropbox link to follow along (https://duke.box.com/s/24j66q5avi2bc3t2wrjjlsz8qetyt0wt):

1) First use the Preprocessing.pynb file to create the annotate.txt file:
2) Your training images should be in the folder keras-frcnn (sample images is present in the Dropbox).  Go to the existing directory and run the following command on terminal:

python train_frcnn.py -o simple -p annotate.txt --num_epochs 50 --hf True --vf True --rot True

3) After training, a hdf5 file would be created with the weigts (a sample weight file is present in the Dropbox )
4) Your test images should be in the folder keras-frcnn/test_images (sample test images in Dropbox)
5) Create an empty folder keras-frcnn/result_imgs to store the output images on test data and run the following command:

python train_frcnn.py -o simple -p annotate.txt

(Sample result images also present in Dropbox)



