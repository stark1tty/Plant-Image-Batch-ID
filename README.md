### 🌿🌿🌿 Plant-Image-Batch-ID 🌿🌿🌿

A streamlined Python script for batch identification of plants from images using the PlantNet API. It processes multiple image formats and efficiently saves the identification results along with confidence scores and common names into a CSV file.

#### Features
- **Batch Processing:** Handles multiple images in a directory.
- **Multiple Image Formats:** Supports `.jpeg`, `.jpg`, `.png`, and `.bmp`.
- **Detailed Output:** Results include species name, score, and common names.

#### Setup and Usage
1. Clone or download this repository to your local machine.
2. Install required Python packages: `pip install os csv requests time`.
3. Set your API key, folder path, and CSV file name in the script.
4. Run the script to process the images and save the results in CSV format.

#### Requirements/Packages
- Python 3.10
- os, csv, requests, time

#### Installation
```python
pip install os csv requests time
```

#### Additional Resources
- [Kutools for Excel](https://www.extendoffice.com/product/kutools-for-excel.html): Useful for inserting images into Excel.
- [QGIS Import Photos Plugin](https://plugins.qgis.org/plugins/ImportPhotos/): For importing locational information from images.
- [ExifTool](https://exiftool.org/): For additional camera data and locational information.
- **Filtering Tips:** Use a confidence interval of >0.1 to eliminate most incorrect matches.

#### Contributing
Feel free to fork this repository and contribute by submitting a pull request.

#### License
This project is licensed under the [MIT License](LICENSE).

#### Acknowledgements
- Script is based on an example from PlantNet's GitHub: [https://github.com/plantnet](https://github.com/plantnet)
- PlantNet API: [https://plantnet.org/](https://plantnet.org/)
