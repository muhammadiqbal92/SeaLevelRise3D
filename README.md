# SeaLevelRise3D
3D visualization and analysis of sea level rise impacts using ArcGIS Pro
# Sea Level Rise 3D Visualization Workflow

This document provides the steps for creating 3D visualizations of sea level rise using ArcGIS Pro.

## Step 1: Data Preparation
1. Import the DEM into ArcGIS Pro (`Data/DEM/`).
2. Load flood scenario rasters or shapefiles into the scene (`Data/FloodScenarios/`).

## Step 2: 3D Scene Setup
1. Open the 3D Scene view in ArcGIS Pro.
2. Add the DEM to create the terrain.
3. Add sea level rise layers as:
   - **Extruded polygons** for water depth.
   - **Transparent surfaces** for inundation levels.

## Step 3: Symbology
1. Apply 3D water symbology (`styles/WaterStyle.lyrx`).
2. Use color ramps for flood scenarios (e.g., blue for shallow, red for deep).

## Step 4: Animation and Export
1. Use the **Animation** tab to create a fly-through of the impacted areas.
2. Export the animation as an MP4 file to `Outputs/Animations/`.
3. Export 3D snapshots or maps to `Outputs/Maps/`.

