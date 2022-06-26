# ovWatch
Overwatch Aimbot powered by Deep Learning Object Detection models

## Models
ovWatch uses the YOLOv5 model for object detection. Currently, enemies are detected under the "Person" class (id:1)
Git Repo: https://github.com/ultralytics/yolov5

The various libraries are used to move the cursor:
- pyautogui
- ctypes.windll


## Backlog
- [X] Barebones image detection with pretrained YOLOv5
- [X] Barebones aimbot functionality (Mouse movement to detected object)
- [ ] Support smoother enemy tracking
- [ ] Support auto screen rotation to detect more enemies
- [ ] Code out logic to determine when to stop firing (left click)
- [ ] Add toggle switch for aimbot
- [ ] Train model on Overwatch images to make it more accurate
- [ ] Support multiple attack types (Continuous hitscan, Burst hitscan, One-tap hitscan, Melee
