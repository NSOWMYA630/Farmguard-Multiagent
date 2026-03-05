# Vision Agent

## Purpose
The Vision Agent analyzes farm images and satellite data to detect trees and vegetation.

## Input
- Farm images uploaded by farmers
- Satellite images
- NDVI vegetation data

## Processing Steps

1. Detect trees from farm images
2. Identify vegetation coverage
3. Estimate tree height and density
4. Calculate estimated biomass

## Output
- Tree count
- Tree species estimation
- Biomass estimation
- Vegetation health index

## Technologies Used

AI Vision Models  
Satellite Data (Sentinel-2)  
NDVI Vegetation Index  
Image Processing Algorithms

## Example Output

{
 "tree_count": 120,
 "vegetation_index": 0.78,
 "estimated_biomass": "4.2 tons"
}
