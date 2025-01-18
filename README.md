This is a project from edge impulse which is used to detect cars.

## How It Works  

1. **Data Preprocessing**  
   - Use a dataset from Kaggle containing 175 Testing images and 1001 Training images https://www.kaggle.com/datasets/sshikamaru/car-object-detection.
   - In "Create Impulse" Align the image's height and width in Edge Impulse with the actual image size, use the Object Detection learning block.

2. **Model Development**  
   - Save the parameters and generate features.
   - Adjust the Neural Network settings through trial and error adding the batch size by the batch size, number of epochs (training cycles), adding a learning rate, picking a % for the Validation set to get the f1 
     score and confusion matrix.

