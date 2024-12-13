# Video Recommender System

This project is a Video Recommender System developed using Python. It leverages machine learning techniques to recommend videos based on user preferences. The primary focus is on dimensionality reduction using Principal Component Analysis (PCA) and clustering with K-Means.

## Features

- Dimensionality reduction with PCA for efficient processing
- Clustering using K-Means to group similar videos
- Visualization of clusters and principal components

## Requirements

- Python 3.7+
- Jupyter Notebook

### Python Libraries

Install the required libraries using the command:

```bash
pip install -r requirements.txt
```

**Included Libraries:**
- pandas
- numpy
- matplotlib
- scikit-learn

## Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone <https://github.com/Siddhartha257/video-recommender.git>
   cd video-recommender
   ```

2. **Install dependencies**:

   Ensure all required Python libraries are installed. Run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the project**:

   Launch Jupyter Notebook and open `video_recommender.ipynb`:

   ```bash
   jupyter notebook
   ```

4. **Run the notebook**:

   Execute the cells in `video_recommender.ipynb` sequentially to:
   - Load the dataset
   - Perform PCA for dimensionality reduction
   - Apply K-Means clustering
   - Visualize the results

5. **Test the system**:

   Modify the input data or parameters to observe changes in clustering and recommendations.

## Files

- `video_recommender.ipynb`: Main notebook containing the implementation.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Documentation and setup instructions (this file).

## Usage

The notebook provides an interactive environment where you can:

- Load and preprocess video-related data.
- Adjust the number of PCA components (`n_components`) for dimensionality reduction.
- Change the number of clusters in K-Means to explore different groupings.
- Visualize clusters and their principal components.

## Notes

- Ensure your dataset is in the correct format before loading.
- Fine-tune the number of components in PCA and clusters in K-Means to optimize results for your specific dataset.
