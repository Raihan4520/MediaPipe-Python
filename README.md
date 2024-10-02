# Pose Landmark Detection and Segmentation using MediaPipe

This repository contains a project that utilizes [MediaPipe](https://developers.google.com/mediapipe) for pose landmark detection and segmentation. The project demonstrates the use of both low-level and high-level APIs from MediaPipe to compare their differences in performance and usability. The results include visualizations of pose landmarks and segmentation masks for each image in the dataset.

## Project Structure

- `Images.zip`: A zip file containing an `Images` folder with 10 images. These images are used as input to detect and visualize pose landmarks and segmentation masks.
- `Pose_Landmark_Detection_Using_MediaPipe.ipynb`: A Jupyter Notebook that contains the Python code for detecting and visualizing pose landmarks and segmentation masks. This notebook leverages MediaPipe's pose solutions and provides a comparison between the high-level and low-level APIs.

## Features

1. **Pose Landmark Detection**:
    - The project detects 33 landmarks of human pose in each image.
    - Visualizations of the detected landmarks are overlaid on the images.
  
2. **Pose Segmentation**:
    - The project generates segmentation masks for each image, highlighting human poses.
    - The segmentation masks are visualized alongside the landmark detection results.

3. **API Comparison**:
    - The code demonstrates the use of both the low-level and high-level APIs from MediaPipe.
    - Detailed comments in the code highlight the differences between the two approaches, allowing for a better understanding of their trade-offs.

## Running the Project

### Google Colab

The code is designed and run in [Google Colab](https://colab.research.google.com), which simplifies the process of setting up the environment. To run the project:

1. Open the notebook in Colab:
    - Go to [Google Colab](https://colab.research.google.com) and upload the `Pose_Landmark_Detection_Using_MediaPipe.ipynb` file.
   
2. Ensure the `Images.zip` file is uploaded to Colab and extracted:
    - You can upload the file directly to Colab and use Python to unzip it within the notebook (check code comments).

3. Run the cells in the notebook to see the pose landmarks and segmentation results.

### Local Environment

To run the project locally, follow these steps (note: additional setup is required to adjust file paths and ensure compatibility):

1. Clone the repository:
    ```bash
    git clone https://github.com/Raihan4520/MediaPipe-Python.git
    ```

2. Install the required dependencies:
    - You will need Python 3.x and Jupyter Notebook.
    - Install the required libraries by running:
      ```bash
      pip install mediapipe opencv-python matplotlib
      ```

3. Extract the `Images.zip` file to get the `Images` folder.

4. Modify the paths in the notebook:
    - Adjust file paths as necessary to ensure the code can access the images and save results locally.

5. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Pose_Landmark_Detection_Using_MediaPipe.ipynb
    ```

6. Run the cells in the notebook to see the pose landmarks and segmentation results.

## Results

For each image in the `Images` folder, the notebook detects and visualizes:
- Pose landmarks (33 key points) overlaid on the original image.
- A pose segmentation mask, highlighting the human figure.

## Code Insights

- The notebook includes detailed comments explaining how MediaPipe's high-level and low-level APIs are used to perform pose detection and segmentation.
- Comparison of both APIs is done to provide insight into the ease of use and flexibility of each approach.

## Acknowledgments

- [MediaPipe](https://mediapipe.dev) by Google for providing the powerful tools to detect and segment human poses.

## Contact

If you have any questions or suggestions, feel free to reach out through the repository's issues or contact me directly.

---

Feel free to explore and modify the code to suit your needs!
