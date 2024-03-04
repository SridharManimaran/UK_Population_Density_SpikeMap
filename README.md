# UK_Population_Density_SpikeMap
Raster Data Processing

This script showcases the processing of raster data for visualizing population distribution in Great Britain. The data, obtained from Kontur, is transformed from vector to raster format using the Lambert projection. With the provided functions, the raster size is calculated based on the bounding box of the population data, ensuring accurate representation. The population data is then rasterized and plotted, providing a comprehensive view of population density across the region. Finally, the raster data is converted into a matrix for further visualization using rayshader, a powerful tool for creating 3D visualizations from raster data.
![Raster Data](https://github.com/SridharManimaran/UK_Population_Density_SpikeMap/blob/main/Raster_map.png?raw=true)

Rendering Process with Rayshader

Utilizing the rayshader package, the script performs a rendering process to generate a high-quality 3D visualization of population distribution. The raster data is converted into a matrix, which is then used to create a height-shaded 3D plot. Parameters such as lighting direction, altitude, and intensity are adjusted to enhance the visual appeal and depth of the rendering. The resulting 3D plot offers an immersive representation of population density in Great Britain, providing valuable insights for spatial analysis and urban planning.
![Rayshader Data](https://github.com/SridharManimaran/UK_Population_Density_SpikeMap/blob/main/british_population_2023.png?raw=true)
