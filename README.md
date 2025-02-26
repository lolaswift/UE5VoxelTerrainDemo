# UE5VoxelTerrainDemo
Unreal Engine 5 procedural voxel terrian example (partially based on Transvoxel™ Algorithm by Eric Lengyel http://transvoxel.org/)
This project provides tools to generate, visualize and in-game change volume terrain using voxels.

![Voxel terrain](https://github.com/bw2012/UE5VoxelTerrainDemo/blob/master/demo.gif?raw=true)

![Voxel cave](https://github.com/bw2012/UE5VoxelTerrainDemo/blob/master/cave_demo.gif?raw=true)

**Master branch tested with Unreal Engine 5.1.1 [Windows 10]**

**Work in progress. Contains some unfinished code and unoptimized parts**

# Download playable demo
UE5 version: [UE5VoxelTerrain-0.0.37.zip](https://cutt.ly/z2yhLnA) 


# Features
* Runtime terrain modification
* Procedural landscape/caves generation
* Level of details (per chunk)
* Foliage
* Up to 65535 terrain materials

# Attention
* Work in progress. Some features is not finished
* Project uses C++20 features

# Usage
1. Install MS Visual Studio 2022
2. Download last stable project or clone repository ```git clone https://github.com/bw2012/UE5VoxelTerrainDemo.git```
3. Open project directory 
4. Download [Content.rar](https://drive.google.com/file/d/1M5g3yNBzTpMd4YA3FUJi72maObA_pDXE/view?usp=share_link) (~2Gb) and unzip it to ```Content``` folder
5. Open project file with Unreal Engine 5
6. Wait for compile UE5 KiteDemo shaders (first run may take long time)

# License
MIT license
