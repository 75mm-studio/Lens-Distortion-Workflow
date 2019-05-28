# Lens Distortion Workflow

## Lens Distortion
1. What is **Lens Distortion**

1. Type
    1. Radial Distortion - 방사왜곡
        1. Barrel Distortion
        2. Pincushion Distortion
            ![pincushion](imgs/pincushion.jpg)
        3. Moustache/Complex Distortion
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

- [다크 프로그래머 :: 카메라 왜곡보정 - 이론 및 실제](https://darkpgmr.tistory.com/31)
