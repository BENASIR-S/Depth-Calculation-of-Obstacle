# Implementation of Stereomatching Algorithm for Depth Calculation of Obstacles

## Project Overview

This project involves the implementation of a stereomatching algorithm to calculate the depth of obstacles. The algorithm uses stereo vision techniques to generate depth maps, which can be utilized in various applications such as robotics, autonomous driving, and 3D reconstruction.

## Features

- **Stereo Image Processing**: Uses a pair of stereo images to calculate the disparity map.
- **Depth Calculation**: Converts disparity information into depth values for obstacle detection.
- **Visualization**: Provides a visual representation of depth information.
- **Voice Output**: Announces the depth of obstacles every 2 seconds to assist users in real-time monitoring.

## Technology Stack

- **JavaScript**: The core programming language used for the implementation of the stereomatching algorithm.
- **Python**: Used alongside JavaScript for image processing tasks with `cv2` and `numpy`.

## Getting Started

### Prerequisites

Ensure you have the following installed on your local development environment:

- Node.js
- npm (Node Package Manager)
- Python (for image processing)
- `opencv-python` and `numpy` libraries

### Installation

1. Navigate to the project directory:
    ```sh
    cd stereomatching-depth-calculation
    ```
2. Install the required Node.js dependencies:
    ```sh
    npm install
    ```
3. Install the required Python libraries:
    ```sh
    pip install opencv-python numpy
    ```

### Running the Project

To run the project locally, use the following command:
 use Command Prompt or Visual studio code.

### Usage

1. Click on the "Toggle Speech" button to generate the voice.
2. View the depth map to analyze obstacle distances.
3. Listen to the voice output, which announces the depth of obstacles every 2 seconds.
