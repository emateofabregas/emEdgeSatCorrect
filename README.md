# emEdgeSatCorrect
![emEdgeSatCorrect_gizmo](https://github.com/user-attachments/assets/f01ff709-cc47-434e-9881-57e8cbd43505)
Gizmo to fix edge artifacts in the DMP layer when you merge the rest of the CG Layers in the ACES colorspace.  
![emEdgeSatCorrect_Knobs](https://github.com/user-attachments/assets/2bc5c0f5-91bd-4513-bb3d-6e563bc1e5ce)
# How to use it:
1. Put this node after your DMP layer and before going to all the CG layers.
2. Connect the 'CG_Alpha' to your layers merged with the 'Channel Merge' node with the union operation.
