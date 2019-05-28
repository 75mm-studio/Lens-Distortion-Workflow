# Lens Distortion Workflow

## Lens Distortion
1. What is **Lens Distortion**

1. Type
    1. Radial Distortion - 방사왜곡
        1. Barrel Distortion
            
            <img src="../imgs/Barrel-Distortion.png" height="250"/> <img src="../imgs/Wine-Barrel.jpg" height="250"/>
            
        2. Pincushion Distortion
        
            <img src="../imgs/Pincushion-Distortion.png" height="250"/> <img src="../imgs/pincushion.jpg" height="250"/>
            
        3. Moustache/Complex Distortion
        
            <img src="../imgs/Wavy-Moustache-Distortion.png" height="250"/>
        
    1. Tangential - 접선왜곡

1. Fix
    1. Grid Shot
    1. Parameter Adjustment

## 3DEqualizer
1. Export Undistorted/Dewarped Plates
1. Export Nuke LD_3DE4 Lens Distortion Node
1. Export Project to Maya


## Maya

### Setup
1. Import 3DE Project
1. Overscan
    1. Film Aperture
    1. Image Plane

### Render
1. Render Settings
    1. Image Size = Undistorted/Dewarped Plate Size

## Nuke

### Install

### Redistort/Distort Node Tree

---

# References
_ [How Lenses Function](https://youtu.be/EL9J3Km6wxI)
- [How Canon EF Lenses Are Made](https://youtu.be/59BfFQuX1rg)
- [다크 프로그래머 :: 카메라 왜곡보정 - 이론 및 실제](https://darkpgmr.tistory.com/31)
- [What is Distortion? - Photography Life](https://photographylife.com/what-is-distortion)
