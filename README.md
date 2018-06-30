# LearningBias

We did this work as an opening for a lecture about learning bias

See LearnigBias - overview.pptx to see our work

## Running on your own
0. Clone
1. Extract the training data from training_data.zip **OR** Create your own dataset and put it under training_data directory with the folder name as the label and all the files inside that match the label, I used "Fatkun Batch Download Image" chrome extension for it 
2. Give +X permissions to both scripts e.g chmod +x train_script.sh, chmod +x test_image.sh 
3. Run train_script.sh to train your network, this will train the network under your tmp folder
3. Run test_image.sh <test-image-path> e.g test_image.sh misleading_dog.jpg
