## ViO

### [model.py](model.py)

VioNet model
Upload model tại đường link sau rồi thay đổi model path muốn dùng ở trong file model.py:
https://drive.google.com/drive/folders/1KC3lBTtMsnCroRsDXVf-se2lFR1kW-vm?usp=sharing

### [backend.py](backend.py)

the process from input to output

`input`: (batch_size)x3x16x112x112 tensor

`output`: class

### [videoloader.py](videoloader.py)

Based on OpenCV

`input`: video path

`output`: clips with 16 frames

### [demo.py](demo.py)

how to run the code

```
python demo.py path_to_video
```
