# License-Plate-Recognition
Automatic License Plates Recognition using Yolov8 and EasyOCR | PyCharm



### Steps to run Code
- Clone the repository.
```
git clone https://github.com/yassineb14/License-Plate-Recognition.git
```
- Goto the cloned folder.
```
cd License-Plate-Recognition
```
- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Run the code with mentioned command below.

 - Run for webcam for testing
 
`python test.py`

 - Run predict for Detecting Licenses

`python predict.py model=best.pt source=images/compus.jpg`

 - Run predict_number for Reading Numbers from Licenses

`python predict_number.py model=best.pt source=images/compus.jpg`

<p align="center">
<img src="https://github.com/yassineb14/License-Plate-Recognition/">
</p>

 - Download best.pt (Result of training)

Download weight: https://drive.google.com/file/d/1WoWDuMFxC7WvfFFvL-zTgQWj-1oM-Y5e/view?usp=share_link#   L i c e n s e - P l a t e - R e c o g n i t i o n  
 