 Overview:
This project focuses on the design and implementation of an algorithm that aligns real-time LiDAR depth maps with pre-stored reference data, such as:
Digital Elevation Models (DEM) – 3D representations of terrain surface.
Optical Images – 2D satellite or orbital photographs.
The algorithm is built to enable real-time localization and mapping in unknown or unmapped environments, such as planetary surfaces.

 Core Objective:
The primary goal is to:
Match real-time LiDAR depth maps with pre-existing DEMs or optical images.
Estimate the sensor's position, orientation, and scale.
Enable robust navigation and situational awareness for applications like space missions, robotics, or autonomous exploration systems.

Features:
Real-time LiDAR data ingestion
Matching pipeline for DEM and/or optical images
Transformation estimation (translation, rotation, scaling)
Visualization of matched data
Performance metrics (e.g., matching accuracy, runtime)

To run the project store all the files on your desktop 
# Step 1: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 2: Install the necessary dependencies.
npm i

# Step 3: Start the development server with auto-reloading and an instant preview.
npm run dev


