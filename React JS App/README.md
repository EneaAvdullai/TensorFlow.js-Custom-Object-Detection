# TensorFlow.js Custom Object Detection

Create your own custom object detection app using TensorFlow.js

## Steps:

1. Clone the repository on your local machine.
2. Login to your Google account and upload your dataset in the following directory strucutre ONLY; to avoid any errors during model training as the notebook is created that is compatible to this format of directory.

```TFJS-Custom-Detection
   |__ images (contains all the training and validation *.jpg image files)
   |__ annotations (contains all the training and validation *.xml annotation files)
   |__ train (contains only the training *.jpg and *.xml files)
   |__ val (contains only the validation *.jpg and *.xml files)
   ```


3. Upload the `Custom_Object_Detection_using_TensorFlow_js.ipynb` notebook on Colab.
4. Run the cells one-by-one by following the instructions.
5. Once the training is complete, download the `model_web` folder on your local machine and copy it inside `TensorFlow.js-Custom-Object-Detection/React JS App/public` directory.
6. Run the following commands.
   - `cd TensorFlow.js-Custom-Object-Detection/React JS App`
   - `npm install`
   - `npm run`
7. Open `localhost:3000` on your web browser and test the model for yourself.
