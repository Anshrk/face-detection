# Face detection I created using Open-CV

## To use to application follow the steps below
---
1. Clone the repository
```python
git clone https://github.com/anshrk/face-detection
cd face-detection
```
2. Installed the required libraries
```python
# use a virtual environment if needed
pip3 install -r requirements.txt
```
3. Use the app
```bash
# detecting an image
python3 face_detect.py <path of the image>
# eg
python3 face_detect.py test/abba.png
python3 face_detect.py test/foo.jpg

# detecting through facecam
python3 live.py
```

### TO BE NOTED
- Pressing any key while the image is in focus will close the application.
- Right-click to save an image.

---
### Made by Ansh
---