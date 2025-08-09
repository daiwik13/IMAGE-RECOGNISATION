Requirements
bash
Copy
Edit
pip install -r requirements.txt
Demo 🌰
Modify the required paths in the main function of inference.py

bash
Copy
Edit
python inference.py
Training (train)
In train.py, change checkpoint_path to your model path

In dataf.py, change training_data_path to your training data path

bash
Copy
Edit
python train.py
Visualization Examples
Example 🌰 1
Original table image, row detection result, and column detection result

Example 🌰 2
Original table image, row detection result, and column detection result

Update 8.17
Modified data preprocessing in dataf.py. Adjust as needed based on your own dataset. (Data augmentation is also important for good results.)

Added post.py as a demo for post-processing. The main idea is to use the set of line segments obtained from the Hough transform (HoughLinesP) to repair broken straight lines.


Others
For training data and pre-trained model, follow the WeChat public account hulugeAI and send a message: table parser

