How to Run
Prepare Dataset
Place your image dataset in Garbage/7class/ with subfolders for each class.

Run Training Notebook
Execute notebook.ipynb to train the model and save the best model as best_model.h5.

Convert to TensorFlow.js
Run the following:

bash
Copy
Edit
tensorflowjs_converter --input_format=keras best_model.h5 modeltfjs/
Deploy on Web
Use modeltfjs/model.json and .bin files in your web app via TensorFlow.js.
