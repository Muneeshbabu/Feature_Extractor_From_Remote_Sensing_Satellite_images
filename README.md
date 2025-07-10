# Feature Extraction from Remote Sensing Satellite Images

This project focuses on the automatic extraction of features from satellite images using deep learning techniques. The system detects and classifies four key features from satellite images:
  Water Bodies
  Roads
  Buildings
  Vegetation

The extracted features are then visualized using a pie chart to show their percentage distribution in the image

   Frontend: HTML, CSS
   Backend: Python (Django/Flask)
   Deep Learning Model: U-Net
   Visualization: Matplotlib (for pie chart)

 Key Features:

- Upload a satellite image through a simple web interface.
- Automatically extract the following features:
  - Water bodies
  - Roads
  - Buildings
  - Vegetation
- Display the percentage of each feature visually using a pie chart.
- Built with a U-Net model trained for semantic segmentation.

 Deep Learning Model - U-Net :

The U-Net model is used for **semantic segmentation**, allowing the system to accurately classify each pixel of the satellite image into one of the four categories. U-Net is effective for image segmentation tasks, especially when training data is limited.

 Output Example :

After processing an image, the output includes:
- Segmented feature mask
- Pie chart showing the percentage area of:
  - Water
  - Roads
  - Buildings
  - Vegetation

 How to Run the Project :

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/feature-extraction-satellite-images.git
   cd feature-extraction-satellite-images

   Install dependencies:

   pip install -r requirements.txt

      Author
      Muneesh Babu



